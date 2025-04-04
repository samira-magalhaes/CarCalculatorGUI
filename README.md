<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="github-style.css">
</head>
<body>

    <h1>Calculadora do Imposto Automóvel e Preço de Venda</h1>

    <p>Este projeto é uma aplicação distribuída que calcula o <strong>imposto</strong> e o <strong>preço de venda</strong> de carros com base no <strong>ano de fabricação</strong> e <strong>cilindrada do motor</strong>.</p>

    <h2>Índice</h2>
    <ul>
        <li><a href="#sobre">Sobre</a></li>
        <li><a href="#como-usar">Como Usar</a></li>
        <li><a href="#instalacao">Instalação</a></li>
        <li><a href="#tecnologias">Tecnologias</a></li>
        <li><a href="#contribuicao-cliente">Contribuição ao Cliente</a></li>
        <li><a href="#licenca">Licença</a></li>
    </ul>

    <h2 id="sobre">Sobre</h2>
    <p>Este projeto tem como objetivo calcular dois valores essenciais para a venda de um carro:</p>
    <ol>
        <li><strong>Imposto</strong>: Calculado com base na <strong>cilindrada do motor</strong> do carro.</li>
        <li><strong>Preço de Venda</strong>: Calculado considerando a <strong>depreciação</strong> do carro ao longo dos anos, com base no <strong>ano de fabricação</strong>.</li>
    </ol>
    <p>A comunicação entre o cliente e o servidor é realizada via <strong>RPC (Remote Procedure Call)</strong>, permitindo que os cálculos sejam feitos no servidor e os resultados retornem ao cliente.</p>

    <h2 id="como-usar">Como Usar</h2>
    <ol>
        <li>Clone o repositório:
            <pre><code>git clone https://github.com/usuario/car-calculator.git
cd car-calculator</code></pre>
        </li>
        <li>Compile os arquivos Java:
            <pre><code>javac ro/tuc/dsrl/ds/handson/assig/two/server/services/*.java
javac ro/tuc/dsrl/ds/handson/assig/two/server/Server.java</code></pre>
        </li>
        <li>Execute o servidor:
            <pre><code>java ro.tuc.dsrl.ds.handson.assig.two.server.Server</code></pre>
        </li>
        <li>Execute o cliente:
            <pre><code>java ro.tuc.dsrl.ds.handson.assig.two.client.communication.CarCalculatorGUI</code></pre>
        </li>
    </ol>

    <h2 id="instalacao">Instalação</h2>
    <p>Clone o repositório:</p>
    <pre><code>git clone https://github.com/usuario/car-calculator.git
cd car-calculator</code></pre>
    <p>Compile os arquivos Java para o servidor e cliente.</p>
    <p>Execute o servidor com:
        <pre><code>java ro.tuc.dsrl.ds.handson.assig.two.server.Server</code></pre>
    </p>
    <p>Execute o cliente com:
        <pre><code>java ro.tuc.dsrl.ds.handson.assig.two.client.communication.CarCalculatorGUI</code></pre>
    </p>

    <h2 id="tecnologias">Tecnologias</h2>
    <ul>
        <li><strong>Java 8+</strong></li>
        <li><strong>RMI (Remote Method Invocation)</strong></li>
        <li><strong>Swing (para a interface gráfica)</strong></li>
    </ul>

    <h2 id="contribuicao-cliente">Contribuição ao Cliente</h2>
    <p>Este projeto oferece uma solução eficaz e eficiente para as concessionárias, vendedores de carros e consumidores que buscam calcular com precisão o imposto devido sobre a compra de veículos e o preço de venda de carros usados. A contribuição principal ao cliente é:</p>
    <ol>
        <li><strong>Facilidade de uso</strong>: Com uma interface gráfica simples e intuitiva, o cliente pode facilmente inserir os dados do carro, como o ano de fabricação e a cilindrada do motor, e obter rapidamente o valor do imposto e do preço de venda.</li>
        <li><strong>Cálculos precisos</strong>: Utilizando um algoritmo de depreciação baseado no ano de fabricação e a cilindrada do motor, o cálculo do preço de venda é feito de maneira automática e precisa.</li>
        <li><strong>Automação e redução de erros</strong>: O sistema automatiza o processo de cálculo, minimizando a possibilidade de erros humanos e melhorando a eficiência no processo de venda de veículos.</li>
    </ol>
    <p>Isso proporciona não apenas uma experiência mais ágil, mas também mais transparente para os clientes e vendedores, garantindo que todos os cálculos necessários sejam realizados corretamente e de maneira rápida.</p>

    <h2 id="licenca">Licença</h2>
    <p>Este projeto está sob a licença MIT. Veja mais em <a href="LICENSE">LICENSE</a>.</p>

</body>
</html>
