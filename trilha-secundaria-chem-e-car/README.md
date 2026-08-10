# Trilha Secundária: Aplicação Prática — Chem-E-Car

Esta pasta contém o material assíncrono de aplicação prática em Python voltado para a análise de dados do projeto **Chem-E-Car**. O objetivo desta trilha é preparar os membros do capítulo para a capacitação avançada e para a modelagem da parada do carrinho da competição.

---

## 📂 Arquivos da Trilha

* **`dados/testes_carrinho.csv`**: Conjunto de dados fictícios contendo o histórico de experimentos (massa de reagente, distância percorrida, tempo e erro de parada).
* **`01_introducao_pandas_matplotlib.ipynb`**: Introdução à manipulação de tabelas com `pandas` e geração de gráficos de dispersão com `matplotlib`.
* **`02_projeto_calibracao_chem_e_car.ipynb`**: Projeto prático guiado para construção do modelo linear de calibração (relação massa vs. distância) usando `numpy`.

---

## 🚀 Como Utilizar

1. Acesse os notebooks diretamente via Google Colab pelos links disponíveis no `README.md` principal na raiz do repositório.
2. Caso esteja executando localmente, garanta que as bibliotecas necessárias estejam instaladas:

```bash
pip install pandas matplotlib numpy

```

3. Os notebooks realizam a leitura direta do arquivo `testes_carrinho.csv` via URL do repositório no GitHub, dispensando o download manual do arquivo de dados para a execução.

---

## 🎯 Objetivos de Aprendizagem

* Ler e inspecionar dados estruturados no formato CSV.
* Filtrar registros e extrair estatísticas descritivas básicas (média, desvio padrão).
* Plotar curvas de calibração experimentais.
* Determinar coeficientes de regressão linear para previsão de massa de reagente em função da distância alvo.
