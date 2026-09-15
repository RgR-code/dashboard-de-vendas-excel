# 📈 Dashboard Executivo de Desempenho de Vendas no Excel

Projeto de Business Intelligence e análise de dados desenvolvido em Microsoft Excel para transformar dados brutos de vendas em uma visão executiva clara, interativa e voltada para a tomada de decisões estratégicas.

---

## 🎯 Objetivo do Projeto
Oferecer a gestores e equipes comerciais um painel visual consolidado para acompanhar os principais indicadores de vendas (KPIs), analisar o desempenho por região, identificar os produtos mais rentáveis e avaliar a performance individual da equipe de vendas.

---

## 🛠️ Estrutura da Solução

### 1. 📊 Aba `Dashboard de Vendas` (Visão Executiva)
* **Cartões de KPIs Principais:**
  * **Faturamento Total (R$):** Receita bruta acumulada.
  * **Lucro Total (R$):** Resultado financeiro líquido.
  * **Margem de Lucro Média (%):** Indicador de rentabilidade das operações.
  * **Volume de Pedidos:** Total de transações comerciais realizadas.
* **Recursos Visuais e Gráficos:**
  * **Gráfico de Colunas:** Faturamento comparativo por Vendedor.
  * **Gráfico de Rosca:** Distribuição de vendas por Categoria de Produto (Eletrônicos, Móveis e Acessórios).
  * **Gráfico de Barras Horizontais:** Performance comercial por Região Geográfica.
  * **Tabela de Ranking:** Consolidação dos melhores resultados da equipe.

### 2. 🗄️ Aba `Base de Dados` (Massa de Dados Operacional)
* Registro de 150 operações de venda contendo: *ID do Pedido, Data, Região, Vendedor, Categoria, Produto, Quantidade e Preço Unitário*.
* **Automação por Fórmulas:** Cálculo automatizado de Faturamento (`Qtd * Preço`), Custo e Lucro Líquido por operação.

### 3. ⚙️ Aba `Parâmetros` (Suporte e Agregação)
* Estrutura de tabelas auxiliares utilizando fórmulas de agregação (`SUMIF`) para alimentar o Dashboard sem comprometer a organização visual.

---

## 🎨 Design e Boas Práticas Utilizadas
* **Paleta Executiva:** Utilização do tema *Dark Navy Blue & Teal* para uma estética limpa, moderna e profissional.
* **Formatação de Dados:** Padrão monetário nacional (`R$ #,##0.00`) e números inteiros formatados.
* **Usabilidade:** Painéis congelados para garantir que cabeçalhos e indicadores permaneçam visíveis durante a navegação.

---

## 📁 Arquivos no Repositório
* `Dashboard_de_Vendas_Executivo.xlsx`: Arquivo do Excel automatizado contendo a base e o dashboard.
* `README.md`: Documentação técnica completa do projeto.

---

## 💻 Tecnologias e Ferramentas
* **Microsoft Excel** (Fórmulas financeiras/estatísticas `SUMIF`, `COUNTA`, agregação de dados e elementos gráficos)
* **Markdown** (Documentação do projeto no GitHub)
