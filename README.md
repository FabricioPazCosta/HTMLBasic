# HTMLBasic
Este repositório é referente a entrega do desafio - HTML BASIC - DIO.me

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML 5 Conceitos Básicos</title>
</head>
<body style="margin: 20px;">
    <center><h1 id="inicio" style="background-color: darkgrey;">HTML - Linguagem Marcação de Texto</h1></center>
    <hr style="border: 10px solid black width 50%;">
    <h2>Índice</h2>
    <ul>
        <li><a href="#client">Entendendo a Comunicação Client/Server</a></li>
        <li><a href="#tags"> Tags Básicas HTML</a></li>
        <li><a href="#listas">Listas Ordenadas e Não ordenadas</a></li>
        <li><a href="#links">Links</a></li>
    </ul>
    <h1 id="client">Entendendo a comunicação Client/Server</h1>    
    <p>
        A comunicação client/server é baseada no protocolo <u style="background-color: blue; color: aliceblue;">HTTP</u>, esse protocolo foi
        desenvolvido com o objetivo de conectar dois pcs e realizar a troca de dados/informações.
        O https é seguro, pois o "s" siguinifica uma comunicação criptografa, ou seja, caso algum 
        meliante venha a capturar os dados, os mesmos estarão embaralhados, de forma que o mesmo não entenda
        o que real se trata aquela informação.
    </p>
    <p>
        O princípio básico de funcionamente é através das requisições http, o cliente solicita uma informação
        e o servidor responde esta solicitação, exemplo quando digitamos o link de uma página web, uma requisição 
        é disparada ao servidor que responde para o cliente, o cliente através do browser mostra a página ao usuário final.
    </p>

    <h1>
        Tags Básicas HTML 
    </h1>
    <p id="tags">
        HTML - Significa linquagem de marcação de texto, é com ela que iremos fazer toda a parte textual e de imagens em nossa
        página. A parte de melhoria no designer fica por conta do CSS, e a lógica por conta do JavaScript.
        Segue abaixo as principais tags para marcação de textos:
    </p>
    <p>
        <ul>
            <li>h1 - Referenta a marcação de títulos.</li>
            <li>h2 - Referente a marcação de subtítulos.</li>
            <li>h3 - Referente a marcação de um cabeçalho de terceiro nível.</li>   
            <li>h4 - Referente a marcação de um cabeçalho de quarto nível nível.</li>   
            <li>h5 - Referente a marcação de um cabeçalho de quinto nível.</li>   
            <li>h6 - Referente a marcação de um cabeçalho de sexto nível.</li>  
            <li>p  - Parágrafo - Criação de um parágrafo</li>    
            <li>a  - Criação de link</li>   
            <li>ol - Criação de lista ordenanada</li>
            <li>ul - Criação de lista não ordenada</li>    
            
        </ul>
        
    </p>

    <h1 id="listas">Listas Ordenadas / Não Ordenadas</h1>
    <small><a href="#inicio">(Voltar)</a></small>
    <p>
        As listas ordenadas são utilizadas para ordenar objetos ou outro tipo de coleção, exemplo:
        <ol>
            <li>Nota 10.0</li>
            <li>Nota 9.0</li>
            <li>Nota 8.0</li>
            <li>Nota 7.0</li>
        </ol>
    </p>
    <p>
        As listas não ordenadas, exemplo:
        <ul>
            <li>Camisa</li>
            <li>Calça</li>
            <li>Bernuda</li>
            <li>Óculos</li>
        </ul>
    </p>
    <h1 id="links">Links</h1>
    <small><a href="#inicio">(Voltar)</a></small>
        <p>No caso para criação de links utilizamos a tag a, exemplo:\<br>

        &lt;a  href="https://www.google.com" target="_blank">Visite o site da google</a>&gt;
        <a  href="https://www.google.com" target="_blank">Visite o site da google</a>
    </p>
       
</body>
</html>
