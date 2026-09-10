# Mineração de Dados — UFC

Trabalhos práticos da disciplina de Mineração de Dados, Departamento de Computação — Prof. José Macedo.

**Grupo:**
- Larissa Vitória Santos Menezes — 553875
- Maria Cecília Alves Castro — 553577
- Francisco Irlisson Ferreira Dias — 581523

## Trabalhos

| Pasta | Trabalho | Descrição |
|---|---|---|
| [`data-profiling/`](./data-profiling) | TP01 | Data Profiling em 5 datasets do scikit-learn com `ydata-profiling` |

## TP01 — Data Profiling em 5 Datasets do scikit-learn

Aplicação do `ydata-profiling` a cinco conjuntos de dados clássicos do scikit-learn, convertendo o relatório automático em decisões concretas de análise e pré-processamento.

### Objetivo

Gerar e interpretar relatórios de profiling para os datasets **Iris**, **Wine**, **Breast Cancer**, **Diabetes** e **California Housing**, seguindo um roteiro fixo de seis etapas, contexto, estrutura, qualidade, distribuições, relações e decisão, de forma a transformar estatísticas descritivas em recomendações de preparação de dados justificadas por evidência.

### Estrutura

| Arquivo | Descrição |
|---|---|
| `Atividade_Profiling_5_Datasets.ipynb` | Notebook com carregamento dos datasets, ficha técnica comparativa e geração dos 5 relatórios |
| `perfil_iris.html` | Relatório de profiling — Iris |
| `perfil_wine.html` | Relatório de profiling — Wine |
| `perfil_breast_cancer.html` | Relatório de profiling — Breast Cancer |
| `perfil_diabetes.html` | Relatório de profiling — Diabetes |
| `perfil_california.html` | Relatório de profiling — California Housing |
| `report.pdf` | Mini-relatório com ficha técnica, achados, análise cruzada, recomendações e limites do profiling |

### Como reproduzir

1. Abrir `Atividade_Profiling_5_Datasets.ipynb` no Google Colab.
2. Executar `Ambiente de execução → Executar tudo`.
3. Os 5 arquivos `perfil_*.html` são gerados automaticamente na pasta de execução.

**Ambiente utilizado:** Python 3.13.15 · pandas 2.2.3 · scikit-learn 1.6.1 · ydata-profiling 4.18.4

