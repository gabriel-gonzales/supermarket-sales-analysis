# Análise de Vendas - Supermercado

## Introdução
Este projeto realiza uma análise exploratória e fornece insights estratégicos para uma empresa fictícia, utilizando um dataset contendo informações de pedidos, clientes, produtos e transações. O objetivo é compreender o perfil dos clientes, avaliar o desempenho das vendas e analisar a eficácia das formas de entrega e pagamento.

## Objetivos
1. **Compreender o perfil dos clientes:** Identificar os segmentos mais recorrentes e analisar os produtos mais comprados por grupo de clientes.
2. **Avaliar o desempenho das vendas:** Determinar os produtos mais lucrativos e identificar variações de lucro por região e forma de pagamento.
3. **Analisar a eficácia das entregas e pagamentos:** Investigar como os métodos de entrega e pagamento impactam no lucro e nas devoluções.

## Metodologia
1. **Exploração e limpeza dos dados:** Tratamento de valores ausentes e adequação de tipos de dados.
2. **Análise exploratória dos dados (EDA):** Geração de gráficos e tabelas para identificação de padrões e tendências.
3. **Geração de insights:** Extração de informações relevantes para suporte à tomada de decisões.

## Ferramentas Utilizadas
- **Python:**
  - Pandas e NumPy para manipulação e análise dos dados.
  - Matplotlib e Seaborn para visualizações.
  - Scipy para análises estatísticas.
- **Jupyter Notebook:** Ambiente de desenvolvimento.

## Principais Insights
### Perfil dos Clientes
- Segmento mais frequente: **Consumer**, seguido por **Corporate** e **Home Office**.
- Produtos mais comprados:
  - **Consumer:** Office Supplies.
  - **Corporate:** Office Supplies.
  - **Home Office:** Office Supplies.

### Desempenho de Vendas
- Categoria mais lucrativa: **Technology**.
- Região com maior lucro: **West**.
- Forma de pagamento mais lucrativa: **COD (Cash on Delivery)**.

### Entregas e Pagamentos
- Forma de entrega mais rentável: **First Class**.
- Maior taxa de devolução: **Standard Class** e pagamento **Online**.

### Tempo de Entrega
- Tempo médio de entrega: **3,69 dias**.

## Visualizações Disponíveis
- Distribuição de segmentos de clientes.
- Produtos mais lucrativos.
- Heatmap de correlação entre variáveis.
- Boxplots para variação de lucro por categoria de produto.

## Como Executar o Projeto
1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/analise-vendas-supermercado.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o notebook em Jupyter:
   ```bash
   jupyter notebook
   ```

## Estrutura do Repositório
```
.
|-- data
|   |-- raw_data.csv
|   |-- cleaned_data.csv
|-- notebooks
|   |-- analise_vendas_supermercado.ipynb
|-- README.md
|-- requirements.txt
```

## Conclusão
Os insights obtidos fornecem uma base sólida para melhorias no desempenho operacional e na satisfação do cliente. O foco em categorias lucrativas, como Technology, e regiões rentáveis pode maximizar os resultados.

## Autor
Este projeto foi desenvolvido como parte de um desafio do Green Team da UFABC.

