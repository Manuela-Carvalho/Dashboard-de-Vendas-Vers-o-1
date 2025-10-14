# 📊 Portfólio de Dashboards em Power BI

Bem-vindo ao meu repositório de projetos em Power BI! 🚀  
Aqui eu documento minha evolução na área de **análise de dados**, mostrando como construo dashboards que **transformam dados em insights** e apoiam a **tomada de decisão estratégica**.

Cada projeto faz parte de uma **série evolutiva**, na qual adiciono novas análises e camadas de complexidade a partir de dados de **vendas e estoque**.

---

## 🗂️ Projetos

### 🔹 V1 – Dashboard de Vendas
📌 **Objetivo:** Analisar o desempenho geral de vendas.  

**KPIs:** Receita total, Nº de vendas, Ticket médio.  
**Visuais:** Receita por forma de pagamento, Top 5 produtos mais vendidos.  

📷 *Print:*  
Dashboard V1  

<img width="1431" height="807" alt="image" src="https://github.com/user-attachments/assets/c0bc5294-abab-4f05-a156-5ba87b43dcfd" />

---

### 🔹 V2 – Produtos + Estoque
📌 **Objetivo:** Integrar dados de **vendas e estoque** para analisar **giro, ruptura e excesso de inventário**, ampliando a visão operacional e financeira do negócio.  

**KPIs:** Giro de estoque, Produtos encalhados, Risco de ruptura, Margem de lucro, Custo médio unitário.  
**Visuais:** Estoque vs. Vendas médias, Produtos com maior margem, Evolução mensal de custo e lucro, Top 10 produtos mais vendidos.  

📈 **Versões do projeto:**  
- **V2.1 – Performance Operacional:** foco em giro, cobertura e produtos parados.  
- **V2.2 – Análise Financeira:** inclusão de métricas de custo, margem e markup.  

🧠 **Principais insights:**  
- Em setembro/2025, o custo médio unitário apresentou aumento de **135%**, acompanhado de elevação proporcional na margem de lucro.  
- A análise combinada de estoque e vendas permitiu **mapear produtos com risco de ruptura e identificar estoques parados**.  
- O resumo gerencial automático passou a traduzir dados em **ações estratégicas** e **interpretações de desempenho**.  

📷 *Prints:*  
Dashboard V2.1  

<img width="1441" height="804" alt="image" src="https://github.com/user-attachments/assets/71ea8822-55a3-4969-ab74-71eb8dbe4bce" />

Dashboard V2.2  

<img width="1433" height="808" alt="image" src="https://github.com/user-attachments/assets/ee88c6eb-81ad-44b0-aebd-fa306ce5e005" />

---

### 🔹 V3 – Insights Estratégicos (próxima etapa)
📌 **Objetivo:** Levar a análise para o nível estratégico, mostrando **oportunidades e riscos** de forma automatizada.  

**Análises previstas:** Receita perdida por ruptura, Projeção de vendas, Ticket médio por produto.  
**Storytelling:** Insights em linguagem de negócio, com interpretação automática dos indicadores.  

---

## 📅 Roadmap da Série

| Versão | Tema | Status |
|--------|------|--------|
| V1 | Dashboard simples de vendas | ✅ Concluído |
| V2 | Produtos + Estoque | ✅ Concluído |
| V3 | Insights Estratégicos | 🔜 Em desenvolvimento |

---

## 🛠️ Tecnologias Utilizadas
- **Power BI** (modelagem e visualização)  
- **Excel / CSV** (dados de vendas e estoque)  
- **GitHub** (documentação e versionamento)  

---

## ✨ Observação
Os dados usados neste repositório são **fictícios e anonimizados**, utilizados apenas para fins de estudo e portfólio.  
Todos os valores apresentados são **simulações**, não representando informações reais de empresas ou clientes.

---

## 👩‍💻 Criado por Manuela Carvalho
📈 Projeto desenvolvido como parte do meu portfólio em **Análise de Dados**, com foco em **interpretação gerencial** e **visualização estratégica**.  

---

# 🧾 Fichas Técnicas

## 🔸 V1 — *Dashboard de Vendas*

| Campo | Detalhes |
|--------|-----------|
| **Título do Dashboard** | Painel de Desempenho — Vendas Gerais |
| **Versão** | V1 |
| **Tipo de Análise** | Comercial |
| **Objetivo** | Criar uma visão inicial do **desempenho de vendas**, consolidando indicadores básicos de receita, volume e ticket médio. Essa versão marca o início da estrutura analítica, servindo como base para as evoluções posteriores. |
| **Principais KPIs** | - Receita Total<br>- Nº de Vendas<br>- Ticket Médio |
| **Fontes de Dados** | Planilha de vendas (Excel/CSV) consolidada e importada para o Power BI |
| **Principais Gráficos e Visuais** | - Indicadores principais (cards) de **Receita**, **Ticket Médio** e **Nº de Vendas**<br>- Gráfico de barras de **vendas por forma de pagamento**<br>- Gráfico de colunas com **Top 5 produtos mais vendidos** |
| **Destaques de Insight** | - Identificação dos produtos mais representativos no faturamento.<br>- Distribuição de vendas entre diferentes **formas de pagamento**.<br>- Definição dos primeiros **indicadores-chave (KPIs)** para acompanhamento mensal. |
| **Aprendizados Técnicos** | - Criação de medidas DAX básicas (Soma de Receita, Contagem de Vendas, Média de Ticket).<br>- Estruturação inicial do **modelo de dados** no Power BI.<br>- Uso de **segmentadores simples** para filtragem interativa. |
| **Período de Análise** | Julho a Outubro de 2025 (dados de exemplo) |
| **Status** | ✅ Concluído |

---

## 🔸 V2.1 — *Performance Operacional*

| Campo | Detalhes |
|--------|-----------|
| **Título do Dashboard** | Painel de Desempenho — Performance Operacional |
| **Versão** | V2.1 |
| **Tipo de Análise** | Operacional |
| **Objetivo** | Avaliar o desempenho do estoque em relação às vendas, identificando produtos com **giro lento**, **excesso de inventário** e **risco de ruptura**. |
| **Principais KPIs** | - Giro de Estoque<br>- Cobertura de Estoque (dias)<br>- Ticket Médio<br>- Receita Total<br>- Lucro<br>- Nº de Vendas |
| **Fontes de Dados** | Planilhas de vendas e estoque (CSV/Excel) integradas ao Power BI |
| **Principais Gráficos e Visuais** | - Série temporal **Estoque vs Venda**<br>- Série temporal **Estoque vs Cobertura**<br>- Gráfico de pizza **OS vs OC** (serviços x ordens de compra)<br>- Gráfico de barras **Margem de Lucro por produto**<br>- Tabela dinâmica com risco de ruptura e cobertura de estoque<br>- **Resumo Gerencial automático** com plano de ação |
| **Destaques de Insight** | - Identificação de produtos **parados ou em excesso**.<br>- Criação de **indicador de risco de ruptura** (estoque baixo x venda média).<br>- Implementação de **resumo gerencial automatizado** com ações recomendadas (D1–D7). |
| **Aprendizados Técnicos** | - Uso de medidas DAX para cobertura de estoque e giro médio.<br>- Aplicação de condicionais em texto dinâmico para **interpretação gerencial automática**.<br>- Refinamento visual com cores contrastantes e hierarquia clara de indicadores. |
| **Período de Análise** | Julho a Outubro de 2025 |
| **Status** | ✅ Concluído |

---

## 🔸 V2.2 — *Análise Financeira*

| Campo | Detalhes |
|--------|-----------|
| **Título do Dashboard** | Painel de Desempenho — Análise Financeira |
| **Versão** | V2.2 |
| **Tipo de Análise** | Financeira e Operacional |
| **Objetivo** | Analisar a **evolução de receita, custo e lucro**, correlacionando com o comportamento do estoque e das margens para apoiar **decisões de precificação e reposição**. |
| **Principais KPIs** | - Receita Total<br>- Lucro Operacional<br>- Custo Médio Unitário (CMV)<br>- Margem (%)<br>- Giro de Estoque |
| **Fontes de Dados** | Base consolidada de vendas e estoque (Excel/CSV) atualizada mensalmente |
| **Principais Gráficos e Visuais** | - Linha de tendência **Faturamento e Lucro Bruto (6 meses)**<br>- Linha comparativa **Receita vs CMV vs Lucro**<br>- Tabela com **status de estoque (parado, ativo, ruptura)**<br>- **Resumo Gerencial automático** com análise textual de margens e pontos de atenção |
| **Destaques de Insight** | - Em setembro/2025, observou-se aumento de **135% no custo unitário médio**, acompanhado de crescimento proporcional na margem de lucro.<br>- A concentração de custos indicou necessidade de **melhoria na gestão de fornecedores**.<br>- Evolução positiva da **rentabilidade mensal** ao longo do período. |
| **Aprendizados Técnicos** | - Construção de medidas DAX de **markup dinâmico e margem proporcional**.<br>- Geração de **texto analítico automático** com variáveis de contexto.<br>- Uso de **cores e contraste** para leitura de tendência financeira. |
| **Período de Análise** | Julho a Outubro de 2025 |
| **Status** | ✅ Concluído |
