<div style="text-align: center;">
  <h1 align="center">Calculadora do Imposto Automóvel e Preço de Venda</h1>
</div>



Este projeto é uma aplicação distribuída que calcula o **imposto** e o **preço de venda** de carros com base no **ano de fabricação** e **cilindrada do motor**.
<br>
<br>

## Índice
<br>


- [Sobre](#sobre)
- [Como Usar](#como-usar)
- [Instalação](#instalação)
- [Tecnologias](#tecnologias)
- [Contribuição ao Cliente](#contribuição-ao-cliente)
- [Licença](#licença)

<br>
<br>

## Sobre
<br>

Este projeto tem como objetivo calcular dois valores essenciais para a venda de um carro:

1. **Imposto**: Calculado com base na **cilindrada do motor** do carro.  
2. **Preço de Venda**: Calculado considerando a **depreciação** do carro ao longo dos anos, com base no **ano de fabricação**.

A comunicação entre o cliente e o servidor é realizada via **RPC (Remote Procedure Call)**, permitindo que os cálculos sejam feitos no servidor e os resultados retornem ao cliente.

<br>
<br>

## Como Usar
<br>

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
<br>

1. Clone o repositório:
    ```bash
    git clone https://github.com/usuario/car-calculator.git
    cd car-calculator
    ```

2. Compile os arquivos Java para o servidor e cliente.

3. Execute o servidor:
    ```bash
    java ro.tuc.dsrl.ds.handson.assig.two.server.Server
    ```

4. Execute o cliente:
    ```bash
    java ro.tuc.dsrl.ds.handson.assig.two.client.communication.CarCalculatorGUI
    ```

<br>
<br>

## Tecnologias
<br>

- **Java 8+**  
- **RMI (Remote Method Invocation)**  
- **Swing (para a interface gráfica)**

<br>
<br>

## Contributo ao Cliente
<br>

Este projeto oferece uma solução eficaz e eficiente para concessionárias, vendedores de carros e consumidores que buscam calcular com precisão o imposto e o preço de venda de veículos usados. A contribuição principal ao cliente inclui:

1. **Facilidade de uso**  
   Interface gráfica simples e intuitiva, permitindo fácil inserção dos dados do carro e obtenção dos resultados.

2. **Cálculos precisos**  
   Baseado em algoritmos de depreciação considerando o ano de fabricação e a cilindrada do motor.

3. **Automação e redução de erros**  
   Minimiza erros humanos, automatizando o processo e otimizando o tempo do usuário.

Essa automação proporciona uma experiência mais ágil e transparente tanto para os clientes quanto para os vendedores.

<br>
<br>

## Licença
<br>

Este projeto está sob a licença MIT. Veja mais em [LICENSE](LICENSE).
