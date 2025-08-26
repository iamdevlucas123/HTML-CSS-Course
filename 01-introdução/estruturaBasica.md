HTML - HyperText Markup Language

Passa o conteúdo da pagina como textos, imagens, Videos e Tabelas. É uma marcação de texto como 
o nome ja diz, e é o componente base da criação de websites.

O conteúdo em HTML é definido por alhumas tags

<h1>Título<h1>
<p>Parágrafo<p>
<img src="imagem.jpg" alt="Minha Figura">

- <h1> é uma tag utilizada para títulos
- <p> é utilizada para paragrafos
- src é a abreviação de Source que siginifica Fonte, onde o arquivo está
- alt é o parametro alternativo, caso a imagem não apareça está vai ser a mensagem que vai aparecer


CSS - Cascading Style Sheet

É usado para estilizar elementos escritos em uma linguagem de marcação como o HTML
Cores, Sombras Tamanhos, Posicionamento.

Na parte de estilo conseguimos defini propriedades de cada tag ou variável.

![alt text](image.png)

- Seletor é quando referenciamos alguma tag, variável ou objeto para estilizar
- Declarações é onde eu defino as propriedades e valor.

ESTRUTURA BÁSICA DE UM DOCUMENTO HTML

<!DOCTYPE html>   O tipo do documento e HTML
<html lang="en">  A lingua primária do site será em inglês
<head>            A parte de configurações
    <meta charset="UTF-8">    Unicode Transformation Format 8 bit que representa qualquer caracter em 8 bits (Charset= conjunto de caracteres)
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> name ="viewport" diz que estamos definindo configurações da "janela de visualização". width=device-width faz com que a largura da pagina se ajuste com a largura da tela do dispositivo como um celular ou computador. initial-scale=1.0 define o zoom inicial como 100%
    <title>Document</title> Titulo da aba
</head>
<body>   a parte de conteudo da pagina
    <h1>Hello World<h1>
</body>
</html>

COMO O HTML E CSS FUNCIONAM

Primeiramente o computador pede para o DNS o IP da url digitada, depois é pedido pro servidor que vai enviar o HTML e o CSS (e todo o código necessário) para a maquina e depois esse código vai sel lido pelo navegador (chrome no caso) e o navegador ira devolver em forma de imagem na tela.


