# Monitoramento Ambiental – Sala de Aula

## 1. Descrição do projeto

Este projeto foi desenvolvido em Python e tem como objetivo simular um sistema de monitoramento das condições ambientais de uma sala de aula.

O programa analisa três fatores:
- Temperatura;
- Luminosidade;
- Ruído.

Os valores são digitados manualmente pelo usuário, sem necessidade de sensores físicos.

## 2. Objetivo

Identificar condições ambientais fora dos limites estabelecidos, apresentar alertas, calcular estatísticas e classificar as condições gerais do ambiente.

## 3. Limites utilizados

- Temperatura: de 21 °C a 26 °C.
- Luminosidade: de 300 a 500 lux.
- Ruído: máximo de 35 dB(A).

Os valores foram definidos como referências para a simulação, considerando normas técnicas relacionadas ao conforto térmico, à iluminação e à acústica de ambientes.

## 4. Funcionamento

O programa solicita a quantidade de leituras e recebe os valores de temperatura, luminosidade e ruído.

Em seguida:
1. Armazena os valores em listas.
2. Verifica se existem condições fora dos limites.
3. Apresenta alertas quando necessário.
4. Calcula média, maior e menor valor de cada parâmetro.
5. Calcula a porcentagem de leituras críticas.
6. Apresenta a classificação geral.
7. Gera um relatório em formato TXT.
8. Permite iniciar uma nova sequência de leituras.

## 5. Tecnologias utilizadas

- Linguagem Python.
- Google Colab.
- Listas e funções.
- Estruturas condicionais e de repetição.
- Arquivos de texto (.txt).

## 6. Como executar

1. Abra o arquivo monitoramento.py em um ambiente Python ou Google Colab.
2. Execute o programa.
3. Informe a quantidade de leituras.
4. Digite os valores solicitados.
5. Consulte os resultados e o relatório gerado.

## 7. Arquivos do projeto

- monitoramento.py: código-fonte do programa.
- relatorio_monitoramento.txt: exemplo de relatório gerado.

## 8. Integrantes

- Nome: [Nome do integrante] – RM: [RM]
- Nome: [Nome do integrante] – RM: [RM]
- Nome: [Nome do integrante] – RM: [RM]

## 9. Observação

A média do ruído é uma média aritmética simples, utilizada apenas como estatística descritiva. O programa é uma simulação educacional e não substitui medições ambientais realizadas com equipamentos adequados.
