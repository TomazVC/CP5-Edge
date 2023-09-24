# Readme - Coleta de Dados de Luminosidade com ESP32 e Postman

Este repositório contém o código em Python utilizado para coletar dados de luminosidade por meio de um ESP32 e Postman. Os dados foram coletados a cada 15 minutos, utilizando o protocolo MQTT para comunicação entre o ESP32 e o Postman.

## Colab Notebook

O código Python pode ser encontrado no seguinte Colab Notebook: [Coleta de Dados de Luminosidade com ESP32 e Postman](https://colab.research.google.com/drive/1kwkfZ6VfcdBlLfB4lGTHZA4vnEhOYOsu?usp=sharing). Este notebook contém o código fonte, documentação e visualizações dos dados coletados.

## Descrição do Projeto

Para a coleta de dados de luminosidade, um dispositivo ESP32 foi utilizado para medir os níveis de luminosidade em intervalos de 15 minutos. Os dados foram transmitidos para o Postman por meio do protocolo MQTT e registrados para posterior análise.

## Processo de Coleta de Dados

O processo de coleta de dados pode ser resumido da seguinte forma:

1. **ESP32**: O ESP32, um microcontrolador Wi-Fi, foi configurado para medir os níveis de luminosidade em um ambiente específico.

2. **MQTT**: O ESP32 foi programado para enviar os dados de luminosidade para um servidor MQTT no Postman em intervalos.

4. **Postman**: O Postman foi usado como um servidor MQTT para receber e registrar os dados enviados pelo ESP32.

5. **Coleta de Dados Contínua**: O ESP32 enviou dados de luminosidade continuamente, 24 horas por dia, durante um período específico.

6. **Análise de Dados**: Os dados coletados podem ser posteriormente analisados para extrair informações úteis, como padrões de luminosidade ao longo do tempo.

## Autor

Este projeto foi desenvolvido pela equipe [SoftForge].
