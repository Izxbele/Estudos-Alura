# 🍎 Análise de Preços de Maçãs com NumPy e Matplotlib

Este projeto foi desenvolvido como parte dos estudos com a biblioteca **NumPy** e tem como objetivo analisar os preços de maçãs ao longo do tempo utilizando ferramentas de manipulação numérica e visualização gráfica.

---

## 📚 O que foi aprendido e aplicado neste projeto

### ✅ Leitura de Dados
- Utilizamos a função `np.loadtxt()` da NumPy para abrir e carregar um arquivo CSV com os preços das maçãs.
  
### ✅ Geração e Manipulação de Sequências Numéricas
- Geramos sequências numéricas com `np.arange()` para facilitar a manipulação dos dados.
- Realizamos a **transposição** dos dados para organizar melhor as informações para análise.

### ✅ Análise Estrutural dos Dados
- Verificamos a **dimensão** e a **forma** dos arrays carregados, entendendo a quantidade de elementos e sua organização.
  
### ✅ Visualização dos Dados
- Utilizamos a biblioteca **Matplotlib** para gerar gráficos e visualizar tendências.
- Separação e seleção de partes específicas dos arrays para análises mais detalhadas (como comparar dados de um único ano ou de uma região específica).

### ✅ Tratamento de Dados Faltantes (NaN)
- Identificamos valores ausentes (NaN) nos dados da cidade de **Kaliningrad**.
- Aprendemos a **interpolar** esses valores utilizando a média entre os valores anterior e posterior ao NaN.

### ✅ Regressão Linear com NumPy
- Iniciamos uma análise de regressão linear para estimar tendências nos preços:
  - Testamos valores para os coeficientes da reta (angular e linear).
  - Utilizamos funções do NumPy como `np.square()`, `np.sum()`, e `np.sqrt()` para calcular diferenças entre arrays.
  - Aprendemos a usar `np.linalg.norm()` para simplificar os cálculos de erros.

### ✅ Fórmulas para Estimar Coeficientes
- Implementamos a **fórmula fechada** para calcular os coeficientes da regressão linear usando operações com arrays NumPy.
- Quando a fórmula fechada não era possível, utilizamos geração de números aleatórios para buscar boas estimativas.

### ✅ Reprodutibilidade
- Aprendemos a gerar números aleatórios com **reprodutibilidade** usando `np.random.seed()`, garantindo que os experimentos possam ser reproduzidos no futuro.

### ✅ Agregação e Salvamento dos Dados
- Finalizamos o projeto **agregando** os dados processados e **salvando** para uso em futuras análises.

---

## 🚀 Ferramentas utilizadas

- [Python 3](https://www.python.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)

---

## 💾 Como executar o projeto

1. Clone este repositório ou baixe os arquivos para sua máquina:

    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```

2. Instale as dependências necessárias:

    ```bash
    pip install numpy matplotlib
    ```

3. Abra o notebook ou o script com uma IDE (VSCode, Jupyter Notebook) ou no Google Colab.

## 📈 Resultado
   - Análises completas sobre os preços das maçãs ao longo do tempo.
   - Gráficos gerados para visualização.
   - Dados limpos e preparados para futuras análises ou novos projetos.
