# Manipulação de Dados com Pandas: Entrada e Saída de Arquivos

Este repositório contém notebooks desenvolvidos como parte do curso **"Pandas: entrada e saída de dados"**, oferecido pela [Alura](https://www.alura.com.br/). O foco do conteúdo está em como importar, tratar e explorar dados a partir de arquivos externos, especialmente arquivos CSV.

## Estrutura do Repositório

- `Pandas_i_o_aula.ipynb`: Notebook com o conteúdo teórico e prático da aula, incluindo exemplos de leitura de arquivos CSV com diferentes estruturas.
- `pandas_i_o_desafios.ipynb`: Notebook contendo desafios práticos para testar e aplicar os conhecimentos sobre leitura de arquivos com a biblioteca Pandas.

## Objetivos

- Aprender a realizar a leitura de arquivos CSV com diferentes formatações.
- Entender parâmetros importantes da função `pandas.read_csv`.
- Lidar com delimitadores, codificações e linhas não relevantes nos arquivos.
- Tornar o processo de leitura de dados mais robusto e adaptável.

## Conteúdos Abordados

- Leitura de arquivos CSV:
  - Delimitadores: vírgula (`,`) e ponto e vírgula (`;`)
  - Codificação de caracteres (e.g. `utf-8`, `ISO-8859-1`)
  - Leitura com `skiprows`, `encoding`, `engine`, entre outros parâmetros
- Identificação e descarte de linhas irrelevantes (cabeçalhos extras, rodapés)
- Correta construção de DataFrames a partir de fontes externas

## Conjuntos de Dados

Os dados utilizados são retirados do repositório oficial da Alura e fazem referência a um conjunto simulado de informações comerciais:

- [`superstore_data.csv`](https://github.com/alura-cursos/Pandas/blob/main/superstore_data.csv)
- [`superstore_data_ponto_virgula.csv`](https://github.com/alura-cursos/Pandas/blob/main/superstore_data_ponto_virgula.csv)

## Requisitos e Instalação

### Ambiente

Este projeto foi desenvolvido em **Python 3** e executado com **Jupyter Notebook**.

### Bibliotecas

- `pandas`

Para instalar a biblioteca necessária:

```bash
pip install pandas
