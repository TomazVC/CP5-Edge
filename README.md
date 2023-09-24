# Readme - Coleta de Dados de Luminosidade com ESP32 e Postman

Este repositório contém o código em Python utilizado para coletar dados de luminosidade por meio de um ESP32 e Postman. Os dados foram coletados a cada 15 minutos, utilizando o protocolo MQTT para comunicação entre o ESP32 e o Postman. Além disso, o STH-Comet, retirado do repositório GitHub STH-Comet, foi utilizado para ler e gerenciar os dados coletados.

## Colab Notebook

O código Python pode ser encontrado no seguinte Colab Notebook: [Coleta de Dados de Luminosidade com ESP32 e Postman](https://colab.research.google.com/drive/1kwkfZ6VfcdBlLfB4lGTHZA4vnEhOYOsu?usp=sharing). Este notebook contém o código fonte, visualizações dos dados coletados e a visualização do gráfico obtido durante a execução do programa.

## Descrição do Projeto

Para a coleta de dados de luminosidade, um dispositivo ESP32 foi utilizado para medir os níveis de luminosidade em intervalos de 15 minutos. Os dados foram transmitidos para o Postman por meio do protocolo MQTT e registrados para posterior análise.

## Arquitetura Completa da Solução da Vinícola
A coleta de dados de luminosidade desempenha um papel fundamental no projeto da vinícola. Este projeto é crucial para monitorar e otimizar o ambiente de crescimento das uvas, uma vez que a luminosidade desempenha um papel significativo no desenvolvimento e qualidade das uvas.

## Importância da Coleta de Dados de Luminosidade:
1. **Crescimento das Uvas:** O crescimento adequado das uvas depende da quantidade e qualidade da luz solar que recebem. A luminosidade afeta diretamente o processo de fotossíntese, que é essencial para a produção de açúcares e outros compostos importantes nas uvas.

2. **Maturação das Uvas:** A luminosidade também desempenha um papel vital na maturação das uvas. A quantidade e intensidade da luz solar influenciam o teor de açúcar, acidez e outros atributos que afetam o sabor e a qualidade das uvas.

3. **Monitoramento Remoto:** O projeto da vinícola exige um monitoramento constante das condições ambientais, incluindo a luminosidade. A coleta de dados de luminosidade por meio do ESP32 e sua transmissão para o Postman permitem que os viticultures monitorem remotamente as condições de crescimento das uvas.

## Benefícios do Projeto:
1. **Controle de Qualidade:** A coleta de dados contínua de luminosidade permite que a vinícola mantenha um controle rigoroso sobre as condições de crescimento das uvas, garantindo a qualidade do produto final.

2. **Tomada de Decisão Informada:** Os dados coletados fornecem informações valiosas para a tomada de decisões informadas sobre irrigação, colheita e outros aspectos do cultivo das uvas.

3. **Eficiência Operacional:** Ao monitorar remotamente as condições de luminosidade, os recursos podem ser alocados de forma mais eficiente, economizando tempo e recursos.

## Processo de Coleta de Dados

O processo de coleta de dados pode ser resumido da seguinte forma:

1. **ESP32**: O ESP32, um microcontrolador Wi-Fi, foi configurado para medir os níveis de luminosidade no ambiente das uvas.

2. **MQTT**: O ESP32 foi programado para enviar os dados de luminosidade para um servidor MQTT no Postman em intervalos de 15 minutos.

3. **Postman**: O Postman foi usado como um servidor MQTT para receber e registrar os dados enviados pelo ESP32.

4. **STH-Comet**: O STH-Comet, obtido do repositório [GitHub STH-Comet](https://github.com/fabiocabrini/fiware), foi utilizado para ler e gerenciar os dados coletados. Ele fornece uma interface para consulta e análise dos dados.

5. **Coleta de Dados Contínua**: O ESP32 enviou dados de luminosidade continuamente, 24 horas por dia, durante um período específico (por exemplo, 24 horas por dia).

6. **Análise de Dados**: Os dados coletados podem ser posteriormente analisados utilizando o STH-Comet para extrair informações úteis, como padrões de luminosidade ao longo do tempo.

## Autor

Este projeto foi desenvolvido pela equipe [SoftForge].
