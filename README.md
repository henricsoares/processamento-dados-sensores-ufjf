# Processamento de Dados de Sensores

Este repositório contém o notebook de simulação e pré-processamento de dados IoT para monitoramento ambiental de uma sala de servidores.

## Conteúdo

- `iot_monitoramento_ambiental_simulacao.ipynb`: notebook Python que gera dados sintéticos de temperatura e umidade, trata faltantes e outliers, aplica média móvel e gera gráficos comparativos.

## Como usar

1. Instale as dependências:

```bash
python3 -m pip install pandas numpy matplotlib
```

2. Abra o notebook no Jupyter ou no Google Colab:

```bash
jupyter notebook iot_monitoramento_ambiental_simulacao.ipynb
```

3. Execute as células do notebook em sequência.

## Saídas geradas

- `grafico_exemplo.png`: gráfico comparativo entre dados brutos e tratados.
- `dados_simulados_tratados.csv`: arquivo CSV com os dados processados.

## Referência

O código de simulação e pré-processamento está associado ao relatório do trabalho apresentado em `artigo.tex` e está documentado neste repositório.

## Repositório

- GitHub: https://github.com/henricsoares/processamento-dados-sensores-ufjf
