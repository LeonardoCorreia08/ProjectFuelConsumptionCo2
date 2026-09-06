<div align="center" id="top"> 
  <h1 align="center">Previsão de Consumo de Combustível e Emissão de CO2</h1>
  <p align="center">Projeto de Machine Learning voltado para Análise de Regressão e previsão de emissões de dióxido de carbono em veículos.</p>
</div>

<hr>

## 📋 Sobre o Projeto

Este projeto utiliza técnicas de Análise Exploratória de Dados (EDA) e Modelos de Regressão em Machine Learning para prever a quantidade de emissão de CO2 de veículos com base em seus atributos físicos e de desempenho, como tamanho do motor, número de cilindros e consumo de combustível.

---

## 📊 Principais Atributos do Dataset (Features)

| Coluna / Recurso | Descrição | Tipo de Dado |
| :--- | :--- | :--- |
| `Engine Size` | Tamanho do motor (em litros) | Numérico (Float) |
| `Cylinders` | Número de cilindros | Numérico (Integer) |
| `Fuel Consumption` | Consumo de combustível (cidade/estrada/combinado) | Numérico (Float) |
| `CO2 Emissions` | Emissões de dióxido de carbono (g/km) - **Variável Alvo (Target)** | Numérico (Float) |

---

## ⚙️ Etapas do Pipeline do Projeto

1. **Análise Exploratória de Dados (EDA):**
   * Verificação de valores nulos e inconsistências.
   * Gráficos de correlação e dispersão para identificar a relação linear entre o tamanho do motor, o consumo de combustível e a emissão de CO2.
2. **Pré-processamento:**
   * Divisão dos dados em conjuntos de treino e teste (ex: 80/20).
   * Normalização ou padronização de variáveis quando necessário.
3. **Modelagem Preditiva:**
   * Treinamento de modelos de Regressão (como Regressão Linear Simples/Múltipla).
   * Avaliação do modelo utilizando métricas padrão: $R^2$ (Coeficiente de Determinação) e RMSE (Raiz do Erro Quadrático Médio).

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

* **Python** (Linguagem principal)
* **Pandas / NumPy** (Manipulação e estruturação de dados)
* **Scikit-Learn** (Construção e avaliação dos modelos de regressão)
* **Matplotlib / Seaborn** (Visualização gráfica dos dados e curvas de regressão)

---

## 🚀 Como Executar o Projeto

1. Certifique-se de ter o Python instalado junto com as bibliotecas necessárias. Instale-as via terminal:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
