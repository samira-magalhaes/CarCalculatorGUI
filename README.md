<h1 style="text-align: center; font-size: 56px; font-weight: bold; color: #4CAF50; text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.2);">Car Tax & Selling Price Calculator</h1>

<p style="text-align: center; font-size: 20px; font-style: italic; color: #555;">Este projeto é uma aplicação distribuída que calcula o <strong>imposto</strong> e o <strong>preço de venda</strong> de carros com base no <strong>ano de fabricação</strong> e <strong>cilindrada do motor</strong>.</p>

<hr style="border: 1px solid #ddd; width: 80%; margin: 30px auto;">

## Índice
- [Sobre](#sobre)
- [Como Usar](#como-usar)
- [Instalação](#instalacao)
- [Tecnologias](#tecnologias)
- [Licença](#licenca)

## Sobre

Este projeto tem como objetivo calcular dois valores essenciais para a venda de um carro:

1. <strong>Imposto</strong>: Calculado com base na <strong>cilindrada do motor</strong> do carro.
2. <strong>Preço de Venda</strong>: Calculado considerando a <strong>depreciação</strong> do carro ao longo dos anos, com base no <strong>ano de fabricação</strong>.

A comunicação entre o cliente e o servidor é realizada via <strong>RPC (Remote Procedure Call)</strong>, permitindo que os cálculos sejam feitos no servidor e os resultados retornem ao cliente.

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

A interface gráfica do cliente será exibida, onde você pode inserir os dados do carro e obter os cálculos de <strong>imposto</strong> e <strong>preço de venda</strong>.

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

- <strong>Java 8+</strong>
- <strong>RMI (Remote Method Invocation)</strong>
- <strong>Swing (para a interface gráfica)</strong>

## Licença

Este projeto está sob a licença MIT. Veja mais em [LICENSE](LICENSE).
