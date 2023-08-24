<h2>Controle de Fluxo - Desafio</h2>

<p>Vamos exercitar todo o conteúdo apresentado no módulo de Controle de Fluxo codificando o seguinte cenário.</p>
<p>O sistema deverá receber dois parâmetros via terminal que representarão dois números inteiros, com estes dois números
    você deverá obter a quantidade de interações (for) e realizar a impressão no console (System.out.print) dos números
    incrementados, exemplo:</p>
<ul>
    <li>Se você passar os números 12 e 30, logo teremos uma interação (for) com 18 ocorrências para imprimir os números,
        exemplo: <code>"Imprimindo o número 1"</code>, <code>"Imprimindo o número 2"</code> e assim por diante.</li>
    <li>Se o primeiro parâmetro for MAIOR que o segundo parâmetro, você deverá lançar a exceção customizada chamada de
        <code>ParametrosInvalidosException</code> com a segunda mensagem: "O segundo parâmetro deve ser maior que o
        primeiro"</li>
</ul>
<ol>
    <li>Crie o projeto <code>DesafioControleFluxo</code></li>
    <li>Dentro do projeto, crie a classe <code>Contador.java</code> para realizar toda a codificação do nosso programa.
    </li>
    <li>Dentro do projeto, crie a classe <code>ParametrosInvalidosException</code> que representará a exceção de negócio
        no sistema.</li>
</ol>