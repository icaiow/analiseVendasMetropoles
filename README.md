# Análise de Dados de Vendas por Cidade

## Descrição do Projeto

Este projeto tem como objetivo realizar uma análise detalhada dos dados de vendas de diferentes cidades (Aracaju, Fortaleza, Natal, Salvador, e Recife). Utilizando as bibliotecas Pandas e Matplotlib em Python, a análise inclui a manipulação, limpeza e visualização dos dados, com o objetivo de identificar padrões de vendas e insights importantes para tomada de decisões estratégicas.

## Estrutura do Projeto

- **datasets/:** Contém os arquivos Excel com os dados de vendas de cada cidade.
   Aracaju.xlsx
   Fortaleza.xlsx
   Natal.xlsx
   Salvador.xlsx
   Recife.xlsx

- **notebooks/:** Contém os notebooks Jupyter com o código da análise.
    ```analise_vendas_cidades.ipynb```: Notebook principal com todas as etapas da análise.

- **README.md:** Este arquivo, que documenta o projeto.

## Tecnologias Utilizadas

- **Python** Linguagem de programação utilizada para a análise de dados.
- **Pandas:** Biblioteca para manipulação e análise de dados.
- **Matplotlib:** Biblioteca para visualização gráfica dos dados.

## Etapas do Projeto

1. Carregamento e Preparação dos Dados:
    Leitura dos arquivos Excel contendo os dados de vendas por cidade.
    Concatenação de todos os datasets em um único dataframe.
    Limpeza de dados, incluindo o tratamento de valores nulos e conversão de tipos de dados.

2. Manipulação dos Dados:

    Criação de novas colunas, como _Receita_ (resultado de *Vendas* * *Qtde_*) e colunas temporais (*Ano_Venda* , *mes_venda*, etc.).
    Agrupamento e agregação dos dados por cidade e ano para análise estatística.

3. Análises Estatísticas:

    Cálculo de valores máximos, mínimos e médias de vendas e receitas.
    Identificação das 3 maiores e menores receitas no dataset.

4. Visualização dos Dados:

    Criação de gráficos de barras, linhas, pizza, e histogramas para facilitar a interpretação dos resultados.
    Exemplos incluem visualização de quantidade de vendas por cidade e evolução das vendas ao longo do tempo.


## Como Usar

### Pré-requisitos
Certifique-se de ter o Python instalado em seu ambiente. As bibliotecas necessárias são:

- pandas
- matplotlib

Para instalar as bibliotecas necessárias, você pode executar o comando:

```bash
pip install pandas matplotlib
```

## Executando o Projeto
1. Clone este repositório:

```bash 
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```
2. Navegue até a pasta do projeto e abra o notebook Jupyter:
```bash
bash cd nome-do-repositorio
jupyter notebook notebooks/analise_vendas_cidades.ipynb
```
3. Execute todas as células no notebook para realizar a análise.

## Conclusões
Este projeto permitiu uma análise abrangente dos dados de vendas, proporcionando insights importantes sobre o comportamento das vendas e da receita ao longo do tempo. As visualizações gráficas auxiliaram na identificação de padrões e tendências, que podem ser usadas para melhorar estratégias de vendas e marketing.

## Contribuições
Sinta-se à vontade para fazer **fork** deste repositório, **abrir issues** ou enviar **pull requests** com sugestões de melhorias ou novas funcionalidades.

Licença
Este projeto está licenciado sob a [MIT License](https://opensource.org/license/mit).
