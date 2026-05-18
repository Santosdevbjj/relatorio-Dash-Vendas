# 📊 Relato Dash Vendas — Análise de Dados com Excel e PowerPoint

![KlabinBiExcel003](https://github.com/user-attachments/assets/1eb07fd3-2391-4bfd-8e56-87079be6ffaf)

**Bootcamp Klabin — Excel e Power BI Dashboards**

---

## 1. Problema de Negócio

Toda jornada em dados começa com uma pergunta simples que não tem resposta fácil: **onde a empresa está ganhando e onde está perdendo dinheiro?**

Responder isso com uma planilha bruta — linhas e mais linhas de transações — é impossível para qualquer gestor sem formação técnica. Os dados estão lá, mas o significado está escondido. Vendas por segmento, lucro por produto, desempenho por país: nenhuma dessas informações aparece sozinha em uma tabela desnormalizada.

O desafio deste projeto foi exatamente esse: **pegar uma base de dados financeiros plana e transformá-la em visualizações que qualquer pessoa consiga ler em 30 segundos** — sem precisar de ferramentas complexas, sem banco de dados, sem código. Apenas Excel, raciocínio analítico e escolhas deliberadas sobre o que mostrar e como mostrar.

---

## 2. Contexto

Este projeto foi desenvolvido como primeiro desafio prático do **Bootcamp Klabin — Excel e Power BI Dashboards**, utilizando a base **Financial Sample** — uma amostra de dados financeiros com informações de vendas, lucro, segmento de clientes, produtos e países.

O objetivo foi duplo: primeiro, **replicar com fidelidade** duas páginas de dashboard já desenvolvidas durante o curso — o que exige compreender não apenas as ferramentas, mas as decisões de design por trás de cada visual. Segundo, **criar uma terceira página original**, aplicando autonomia analítica para explorar dimensões geográficas dos dados que as páginas anteriores não cobriam.

O resultado final foi apresentado em formato de slides no PowerPoint, simulando uma entrega profissional de análise de dados — o mesmo fluxo que analistas e consultores usam para comunicar resultados a stakeholders não técnicos.

> **Nota sobre a stack:** este projeto usa Excel e PowerPoint intencionalmente — não por limitação, mas porque são as ferramentas mais presentes no ambiente corporativo real. Saber extrair análise de qualidade do Excel é uma habilidade prática que antecede e complementa o domínio de ferramentas mais avançadas como Power BI.

---

## 3. Premissas da Análise

Para o desenvolvimento dos dashboards, as seguintes premissas foram adotadas:

- **A base Financial Sample é a única fonte de verdade.** Nenhum dado foi alterado ou imputado — todas as visualizações refletem exatamente o que está na base original.
- **Replicar não é copiar — é compreender.** As páginas 1 e 2 foram replicadas com atenção às escolhas de cada visual: por que gráfico de barras para vendas por segmento? Por que cartões para KPIs totais? Entender a intenção por trás de cada decisão de design foi tão importante quanto reproduzir o resultado visual.
- **A página original (3) precisava agregar, não repetir.** O critério para os visuais da página 3 foi explorar uma dimensão ainda não coberta pelas páginas anteriores — o que levou à escolha de visualizações geográficas (mapas por país) e de composição de lucro por segmento.
- **Tooltips como camada extra de informação.** Todos os visuais foram configurados com dicas de ferramentas (tooltips) relevantes — seguindo a premissa de que o dashboard deve responder a pergunta inicial e permitir aprofundamento sem trocar de página.

---

## 4. Estratégia da Solução

A construção seguiu três etapas encadeadas:

**Etapa 1 — Análise exploratória da base**
Antes de criar qualquer gráfico, a base Financial Sample foi inspecionada para entender suas dimensões: quais campos existem, o que cada um representa, quais combinações fazem sentido analítico. Essa etapa definiu quais perguntas os dashboards seriam capazes de responder.

**Etapa 2 — Replicação das páginas 1 e 2 com intencionalidade**
As duas páginas do curso foram replicadas prestando atenção às decisões de design originais: escolha de tipo de visual por cada métrica, hierarquia de KPIs nos cartões, posicionamento dos filtros interativos (país, segmento, produto) e nomeação clara e contextual de cada elemento.

**Etapa 3 — Criação da página 3 original**
Com autonomia total, foram escolhidas visualizações geográficas para explorar a dimensão de país — que as páginas anteriores cobriam apenas como filtro, nunca como protagonista. Dois mapas (vendas/unidades por país e lucro por país) e um gráfico de pizza (lucro por segmento) completaram a análise com uma perspectiva diferente dos mesmos dados.

**Etapa 4 — Apresentação em PowerPoint**
Os resultados foram consolidados em slides simulando uma entrega profissional: contexto do problema, metodologia, principais achados e recomendações — o mesmo formato usado por analistas de dados em apresentações para liderança.

---

## 5. Decisões Técnicas

**Por que Excel e não Power BI diretamente?**
Este projeto marca o início da jornada no bootcamp — e Excel é o ponto de partida correto. Dominar visualização de dados no Excel força o analista a pensar nos fundamentos: quais dados alimentam cada visual, como os filtros interagem, como a hierarquia visual guia o olhar do leitor. Power BI abstrai parte desse processo; o Excel o torna explícito. Projetos mais avançados do portfólio já utilizam Power BI, DAX e modelagem dimensional — este é o registro de onde tudo começou.

**Por que mapas na página original?**
As páginas 1 e 2 cobrem segmento e produto com gráficos de barras e colunas — mas a dimensão geográfica aparecia apenas como filtro, invisível para quem não interagia com o dashboard. A escolha dos mapas na página 3 foi deliberada: mostrar que os mesmos dados têm uma história diferente quando analisados pela lente do país — e que explorar ângulos não óbvios é parte do trabalho analítico.

**Por que PowerPoint para a apresentação final?**
Dados que não são comunicados não geram decisão. A entrega em PowerPoint replica o fluxo real de trabalho de um analista: o dashboard responde às perguntas técnicas, mas a apresentação é o que chega ao tomador de decisão. Separar as duas camadas — análise e comunicação — é uma competência profissional, não apenas uma formalidade de bootcamp.

**O que eu faria diferente hoje?**
Migraria toda a análise para **Power BI**, substituindo os gráficos estáticos do Excel por visuais interativos com filtros cruzados, medidas DAX para KPIs dinâmicos e publicação no Power BI Service para acesso remoto. A estrutura de perguntas de negócio que orientou este projeto já está correta — a evolução é na camada de ferramentas, não no raciocínio analítico.

---

## 6. Insights do Desenvolvimento

Três aprendizados marcaram este projeto:

- **Replicar bem é mais difícil do que parece.** Reproduzir um dashboard existente com fidelidade exige entender cada decisão de design — por que aquele gráfico, por que aquela cor, por que aquele KPI em destaque. Esse exercício ensinou mais sobre boas práticas de visualização do que criar um dashboard do zero com total liberdade.
- **O visual certo depende da pergunta, não da ferramenta.** A escolha de mapas para a página original não foi por estética — foi porque a pergunta "como as vendas se distribuem geograficamente?" pede um visual espacial. Essa lógica de "pergunta → visual adequado" é o raciocínio que separa análise de dados de colagem de gráficos.
- **Apresentar é tão importante quanto analisar.** Montar o PowerPoint revelou gaps na análise: momentos em que um número precisava de contexto, onde faltava uma comparação ou onde um visual não sustentava a narrativa. A apresentação funcionou como revisão crítica do próprio trabalho — uma prática que ficou nos projetos seguintes.

---

## 7. Resultados

Com os dashboards e a apresentação implementados, o projeto entrega:

- ✅ **3 páginas de dashboard** em Excel: 2 replicadas com fidelidade ao modelo do curso + 1 original com perspectiva geográfica
- ✅ **5 KPIs monitorados:** Total de Vendas, Total de Lucro, Total de Unidades Vendidas, Vendas por Segmento e Lucro por Produto
- ✅ **Filtros interativos** por País, Segmento e Produto nas páginas 1 e 2
- ✅ **Visualizações geográficas originais** na página 3: vendas/unidades por país e lucro por país
- ✅ **Apresentação em PowerPoint** estruturada como entrega profissional para stakeholders não técnicos

---

## 8. Próximos Passos

Este projeto é o ponto de partida. Os demais repositórios do portfólio documentam a evolução natural desta jornada:

- [ ] **Migrar para Power BI** com medidas DAX, filtros cruzados e publicação no Power BI Service *(já realizado em [`dashboardGerencial`](https://github.com/Santosdevbjj/dashboardGerencial) e [`dashboardEcommerceDax`](https://github.com/Santosdevbjj/dashboardEcommerceDax))*
- [ ] **Adicionar modelagem dimensional** (Star Schema) para suportar análises mais complexas *(já realizado em [`dashboardStarShema`](https://github.com/Santosdevbjj/dashboardStarShema))*
- [ ] **Integrar com banco de dados em nuvem** para eliminar dependência de arquivos estáticos *(já realizado em [`dashboardCorporativo`](https://github.com/Santosdevbjj/dashboardCorporativo) com MySQL na Azure)*
- [ ] Explorar análises preditivas com séries temporais sobre os dados de vendas

---

## 🛠️ Ferramentas Utilizadas

| Ferramenta | Finalidade |
|---|---|
| Microsoft Excel | Criação dos dashboards, gráficos e filtros interativos |
| Microsoft PowerPoint | Apresentação dos resultados em formato profissional |
| GitHub | Versionamento e documentação do projeto |

---

## 📊 Visuais Criados

**Páginas 1 e 2 — Replicadas**

| Visual | Dimensão Analisada |
|---|---|
| Gráfico de barras | Vendas por Segmento |
| Gráfico de colunas | Lucro por Produto |
| Cartões KPI | Total de Vendas, Total de Lucro, Total de Unidades Vendidas |
| Filtros interativos | País, Segmento, Produto |

**Página 3 — Original**

| Visual | Dimensão Analisada |
|---|---|
| Mapa 1 | Soma de Vendas e Unidades Vendidas por País |
| Mapa 2 | Soma de Lucro por País |
| Gráfico de pizza | Lucro por Segmento |

---

## 📂 Como Visualizar o Projeto

1. Abra `Dashboard_Excel.xlsx` para explorar os dashboards interativos no Excel
2. Visualize a apresentação final em `RelatoDashVendas.pptx`
3. Consulte a base de dados original em `Financial Sample (3).xlsx`


---

## 📄 Licença

Este projeto está licenciado sob a **MIT License** — consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## Autor

**Sergio Santos**

[![Portfólio](https://img.shields.io/badge/Portfólio-Sérgio_Santos-111827?style=for-the-badge&logo=githubpages&logoColor=00eaff)](https://portfoliosantossergio.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sérgio_Santos-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/santossergioluiz)
