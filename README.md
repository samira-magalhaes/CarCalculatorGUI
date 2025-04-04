<div align="center">
  <h1>Calculadora do Imposto Automóvel e Preço de Venda</h1>
</div>

<br>
<br>

Este projeto é uma aplicação distribuída que calcula o **imposto** e o **preço de venda** de carros com base no **ano de fabricação** e **cilindrada do motor**.

## Índice

- [Sobre](#sobre)
- [Como Usar](#como-usar)
- [Instalação](#instalacao)
- [Tecnologias](#tecnologias)
- [Contribuição ao Cliente](#contribuicao-ao-cliente)
- [Licença](#licenca)
<br>
<br>

## Sobre

Este projeto tem como objetivo calcular dois valores essenciais para a venda de um carro:

1. **Imposto**: Calculado com base na **cilindrada do motor** do carro.
2. **Preço de Venda**: Calculado considerando a **depreciação** do carro ao longo dos anos, com base no **ano de fabricação**.

A comunicação entre o cliente e o servidor é realizada via **RPC (Remote Procedure Call)**, permitindo que os cálculos sejam feitos no servidor e os resultados retornem ao cliente.
<br>
<br>

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
<br>
<br>

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
<br>
## Tecnologias

- **Java 8+**
- **RMI (Remote Method Invocation)**
- **Swing (para a interface gráfica)**
<br>
## Contribuição ao Cliente

Este projeto oferece uma solução eficaz e eficiente para as concessionárias, vendedores de carros e consumidores que buscam calcular com precisão o imposto devido sobre a compra de veículos e o preço de venda de carros usados. A contribuição principal ao cliente é:

1. **Facilidade de uso**: Com uma interface gráfica simples e intuitiva, o cliente pode facilmente inserir os dados do carro, como o ano de fabricação e a cilindrada do motor, e obter rapidamente o valor do imposto e do preço de venda.
2. **Cálculos precisos**: Utilizando um algoritmo de depreciação baseado no ano de fabricação e a cilindrada do motor, o cálculo do preço de venda é feito de maneira automática e precisa.
3. **Automação e redução de erros**: O sistema automatiza o processo de cálculo, minimizando a possibilidade de erros humanos e melhorando a eficiência no processo de venda de veículos.

Isso proporciona não apenas uma experiência mais ágil, mas também mais transparente para os clientes e vendedores, garantindo que todos os cálculos necessários sejam realizados corretamente e de maneira rápida.
<br>
<br>
## Licença

Este projeto está sob a licença MIT. Veja mais em [LICENSE](LICENSE).
