# Recetor OFDM IEEE 802.11a — GNU Radio

## Descrição do Projeto

Este projeto é desenvolvido no âmbito da unidade curricular de **Comunicações Digitais**, do Mestrado de Engenharia Eletrotécnica e de Computadores da Faculdade de Engenharia da Universidade do Porto (FEUP).

O principal objetivo consiste no estudo, análise e experimentação de um recetor OFDM baseado na norma IEEE 802.11a, utilizando a plataforma GNU Radio.

O trabalho tem como referência a implementação de código aberto desenvolvida por Bastian Bloessl e colaboradores, permitindo explorar as diferentes etapas do processamento de sinais num sistema de comunicação Wi-Fi.

## Objetivos

- Compreender a arquitetura e o funcionamento de um recetor OFDM IEEE 802.11a.
- Estudar os métodos de deteção e sincronização de tramas.
- Analisar os algoritmos de correção de desvios de frequência e fase.
- Compreender o alinhamento dos símbolos OFDM e a utilização da FFT.
- Estudar os processos de estimação e equalização do canal.
- Analisar os mecanismos de desmodulação e descodificação dos dados recebidos.
- Realizar simulações e experiências práticas no GNU Radio.
- Documentar os procedimentos, resultados e conclusões ao longo do desenvolvimento do projeto.

## Ambiente de Desenvolvimento

O projeto utiliza as seguintes ferramentas e tecnologias:

- **Sistema operativo:** Windows 11
- **Plataforma SDR:** GNU Radio 3.10
- **Gestor de ambientes e dependências:** Radioconda
- **Módulos adicionais:** gr-ieee802-11 e gr-foo
- **Editor de código:** Visual Studio Code
- **Controlo de versões:** Git e GitHub
- **Hardware SDR:** ADALM-PLUTO (para eventuais testes experimentais)

## Estrutura do Repositório

- **grc/** — Diagramas de processamento de sinal desenvolvidos no GNU Radio Companion.
- **scripts/** — Scripts Python e código auxiliar utilizado nas experiências.
- **resultados/** — Gráficos, capturas de ecrã e resultados experimentais.
- **docs/** — Documentação técnica, explicações e notas relativas ao desenvolvimento do projeto

## Referências

1. Bloessl, B., Segata, M., Sommer, C., & Dressler, F. (2013). *An IEEE 802.11a/g/p OFDM Receiver for GNU Radio*. Proceedings of the Second Workshop on Software Radio Implementation Forum (SRIF '13).

2. [gr-ieee802-11 — Repositório GitHub](https://github.com/bastibl/gr-ieee802-11)

3. [gr-foo — Repositório GitHub](https://github.com/bastibl/gr-foo)