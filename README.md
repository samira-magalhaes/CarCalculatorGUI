# <h1 style="text-align: center; font-size: 42px; font-weight: bold; color: #4CAF50; text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.2); margin-top: 40px; margin-bottom: 20px;">Calculadora do imposto automóvel e do preço de venda</h1>

Este projeto é uma aplicação distribuída que calcula o **imposto** e o **preço de venda** de carros com base no **ano de fabricação** e **cilindrada do motor**.

## Índice
- [Sobre](#sobre)
- [Como Usar](#como-usar)
- [Instalação](#instalacao)
- [Tecnologias](#tecnologias)
- [Licença](#licenca)

## Sobre

Este projeto tem como objetivo calcular dois valores essenciais para a venda de um carro:

1. **Imposto**: Calculado com base na **cilindrada do motor** do carro.
2. **Preço de Venda**: Calculado considerando a **depreciação** do carro ao longo dos anos, com base no **ano de fabricação**.

A comunicação entre o cliente e o servidor é realizada via **RPC (Remote Procedure Call)**, permitindo que os cálculos sejam feitos no servidor e os resultados retornem ao cliente.

## Como Usar

1. Clone o repositório:
    ```bash
    git clone https://github.com/usuario/car-calculator.git
    cd car-calculator
    ```

2. Compile os arquivos Java:
    - Para o servidor:
    ```bash
    javac ro/tuc/dsrl/ds/handson/assig/two/server/services/*.java
    javac ro/tuc/dsrl/ds/handson/assig/two/server/Server.java
    ```
    - Para o cliente:
    ```bash
    javac ro/tuc/dsrl/ds/handson/assig/two/client/communication/*.java
    ```

3. Execute o servidor:
    ```bash
    java ro.tuc.dsrl.ds.handson.assig.two.server.Server
    ```

4. Execute o cliente:
    ```bash
    java ro.tuc.dsrl.ds.handson.assig.two.client.communication.CarCalculatorGUI
    ```

A interface gráfica do cliente será exibida, onde você pode inserir os dados do carro e obter os cálculos de **imposto** e **preço de venda**.

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/usuario/car-calculator.git
    cd car-calculator
    ```

2. Compile os arquivos Java para o servidor e cliente.

3. Execute o servidor com:
    ```bash
    java ro.tuc.dsrl.ds.handson.assig.two.server.Server
    ```

4. Execute o cliente com:
    ```bash
    java ro.tuc.dsrl.ds.handson.assig.two.client.communication.CarCalculatorGUI
    ```

## Tecnologias

- **Java 8+**
- **RMI (Remote Method Invocation)**
- **Swing (para a interface gráfica)**

## Licença

Este projeto está sob a licença MIT. Veja
