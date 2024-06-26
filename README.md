# testes com K6
- Contexto: testes de carga realizados para o projeto de Automatização de testes do módulo 9 de Eng de Software do Inteli.
- Endpoint escolhido: POST de distribuições
- Teste: 30 minutos e carga de 10000 usuários.
## 1. Tecnologias utilizadas
- K6:
  - Ferramenta utilizada para a realização de testes de carga
  - Possibilita a simulação de tráfego HTTP para avaliar o desempenho dos endpoints do projeto desenvolvido.
## 2. Conceitos apendidos
### Testes de carga
- Os testes de carga são uma forma de avaliar o desempenho do sistema desenvolvido sob diferentes condições de cargas, de forma simulata.
- Eles conseguem simular como se X usuários estivessem fazendo requisições em um X período de tempo, algo que seria inviável de testar manualmente, com carga humana.
- Os principais objetivos são:
  - identificar os limites operacionais do sistema;
  - detectar gargalos de desempenho;
  - garantir que a aplicação possa lidar com sua carga prevista de forma eficiente e confiável.
### Resultados e Relatório gerado
Resultado: 
- O endpoint de POST de distribuições de pesquisas demonstrou ser capaz de lidar de forma eficiente com uma carga simulada de 0.000 usuários durante o período de teste de 30 minutos. 
- O tempo de resposta e taca de erros permaneceram dentro dos limietes aceitáveis.

![output](./assets/output.png)
- Foi utilizado a ferramenta K6 HTML Report Exporter para gerar um relatório visual com os resultados dos testes desenvolvidos.
- Docs completa da API utilizada: https://github.com/benc-uk/k6-reporter
![k6](./assets/img1.png)
![k6](./assets/img2.png)
