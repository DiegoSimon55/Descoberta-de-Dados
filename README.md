# Projeto de Análise de Dados de Supermercado

Este projeto utiliza Python e bibliotecas como **Pandas**, **Matplotlib** e **Plotly** para analisar dados de um supermercado, incluindo informações sobre preços e descontos por categoria de produto e marca.

## Estrutura do Projeto

1. **Importação de Bibliotecas e Carregamento de Dados**
   - Carrega o arquivo CSV `MODULO7_PROJETOFINAL_BASE_SUPERMERCADO.csv` usando `Pandas`.
   - Exibe as primeiras linhas do DataFrame e a lista de colunas para garantir que os dados foram carregados corretamente.

2. **Análise de Preços por Categoria**
   - Calcula a média e a mediana dos preços (`Preco_Normal`) para cada categoria de produto.
   - Exibe a quantidade total de categorias.

3. **Desvio Padrão por Categoria**
   - Calcula o desvio padrão dos preços por categoria para identificar a variabilidade dos preços em cada categoria.
   - Ordena as categorias com maior desvio padrão para destacar aquelas com maior variação de preços.

4. **Visualização: Boxplot de Preços da Categoria Lacteos**
   - Filtra os dados para a categoria "lacteos" e cria um gráfico de **boxplot** para visualizar a distribuição dos preços.
   - O gráfico exibe a mediana dos preços com uma anotação e utiliza uma paleta de cores personalizada para uma melhor visualização.

5. **Análise de Descontos por Categoria**
   - Calcula a média de desconto para cada categoria e exibe um gráfico de barras para mostrar a média de desconto por categoria.
   - Adiciona rótulos de valor em cada barra para facilitar a leitura.

6. **Visualização: Gráfico de Pizza Interativo**
   - Filtra os dados para remover valores de desconto iguais a 0 e calcula a média de desconto para cada combinação de categoria e marca.
   - Cria um gráfico de **pizza interativo** usando `Plotly`, exibindo a média de desconto por categoria.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal do projeto.
- **Pandas**: Para manipulação e análise dos dados.
- **Matplotlib**: Para criar gráficos de barras e boxplot.
- **Plotly**: Para criar gráficos interativos, como o gráfico de pizza.

## Como Executar o Projeto

1. Clone o repositório para o seu ambiente local.
2. Certifique-se de que as bibliotecas necessárias estão instaladas:
   ```bash
   pip install pandas matplotlib plotly
   ```
3. Abra o arquivo `.ipynb` no Jupyter Notebook e execute as células sequencialmente.

## Visualizações

1. **Boxplot**: Mostra a distribuição dos preços da categoria "lacteos", destacando a mediana.
2. **Gráfico de Barras**: Exibe a média de desconto por categoria.
3. **Gráfico de Pizza Interativo**: Visualiza a média de desconto agrupada por categoria e marca.

## Observações

- Este projeto está configurado para rodar em um ambiente Jupyter Notebook.
- Os dados de entrada estão no arquivo CSV `MODULO7_PROJETOFINAL_BASE_SUPERMERCADO.csv`.
- Certifique-se de ajustar o caminho do arquivo CSV no código se estiver rodando em um ambiente diferente.

## Contribuição

Contribuições são bem-vindas. Para isso:
1. Faça um fork do projeto.
2. Crie uma nova branch (`git checkout -b feature/nome-da-feature`).
3. Faça o commit das suas alterações (`git commit -m 'Adiciona nova feature'`).
4. Envie para a branch principal (`git push origin feature/nome-da-feature`).
5. Abra um Pull Request.
