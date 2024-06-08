
#  Projeto Desafio: Básico HTML e CSS

##  Visão Geral

Este projeto é uma página web simples que promove pacotes de viagens da empresa fictícia "Flutuar". 
A página é composta por um cabeçalho, uma imagem principal, um título, descrições e um rodapé com 
links para destinos, ofertas e contato por email.


##  Tecnologias Utilizadas

-  **HTML5**: Utilizado para estruturar o conteúdo da página.

-  **CSS3**: Utilizado para estilizar o conteúdo da página.

-  **Google Fonts**: Utilizado para importar fontes externas.

##  Estrutura do HTML

    <!DOCTYPE  html>
    
    <html  lang="pt-br">
    
    <head>
    
    <meta  charset="UTF-8">
    
    <link  rel="preconnect"  href="https://fonts.googleapis.com">
    
    <link  rel="preconnect"  href="https://fonts.gstatic.com"  crossorigin>
    
    <meta  name="viewport"  content="width=device-width, initial-scale=1.0">
    
    <title>Page basic html e css</title>
    
    <link  href="https://fonts.googleapis.com/css2?family=Dosis:wght@200..800&display=swap"  rel="stylesheet">
    
    <link  href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap"  rel="stylesheet">
    
    <link  rel="stylesheet"  href="./css/styles.css">
    
    <link  rel="shortcut icon"  href="img/favicon.svg"  type="image" />
    
    </head>
    
    <body>
    
    <main>
    
    <img  src="./img/img1.png"  alt="globo do mundo e uma figura de uma garota tocando no globo">
    
    <h1>O seu próximo <span>destino</span> pode estar aqui...</h1>
    
    <p>
    
    Aqui você encontra uma seleção de <span  class="bold">pacotes completos</span> para as suas férias!
    
    </p>
    
    <p>
    
    Na <span  style="color:#828282; font-weight: bold;">Flutuar</span> você encontra pacotes de viagens nacionais e internacionais que <br/>
    
    incluem: passagens aéreas, hotéis, café da manhã, e até seguro viagem com <br/> <span  class="bold">preços arrasadores</span>!
    
    </p>
    
    <p>
    
    Se você ainda não tem um destino definido, confira nossa seção de ofertas.
    
    </p>
    
    </main>
    
    <footer>
    
    <div  id="line"></div>
    
    <div  id="contatos">
    
    <a  class="bold"  href="http://"  target="_blank">Destinos</a>
    
    <a  class="bold"  href="http://"  target="_blank">Ofertas</a>
    
    <a  class="bold"  href="mailto:contato@example.com">Contato</a>
    
    </div>
    
    <img  src="./img/Wave.svg"  alt="É uma onda cinza ondulando suavemente.">
    
    </footer>
    
    </body>
    
    </html>

  
  

### Explicação do HTML

  

- <!DOCTYPE  html>: Declaração do tipo de documento, especificando que estamos utilizando HTML5.

- <html  lang="pt-br">: Início do documento HTML com a especificação do idioma.

- <head>: Contém metadados sobre o documento, incluindo links para fontes externas e o arquivo de estilos CSS.

- <body>: Contém o conteúdo visível da página.

- <main>: Seção principal da página, incluindo imagem, título e descrições.

- <footer>: Rodapé com links para destinos, ofertas e contato.

  

### Estilos CSS

      
    
    body {
    
    font-family: 'Open sans', sans-serif;
    
    font-size: 15px;
    
    color: #828282;
    
    margin: 0;
    
    text-align: center;
    
    }
    
      
    
    main {
    
    width: 626px;
    
    margin: 64px auto;
    
    }
    
      
    
    h1 {
    
    font-family: "Dosis", sans-serif;
    
    font-weight: normal;
    
    color: #3F3D56;
    
    }
    
      
    
    h1 span {
    
    color: #EE24FF;
    
    font-weight: bold;
    
    }
    
      
    
    #line {
    
    width: 391px;
    
    height: 0;
    
    border: 1px solid #ECEFF2;
    
    margin: 0 auto 8px;
    
    }
    
      
    
    .bold {
    
    font-weight: bold;
    
    color: #3F3D56;
    
    }
    
      
    
    footer a + a {
    
    margin-left: 43px;
    
    }
    
      
    
    a {
    
    text-decoration: none;
    
    }
    
      
    
    footer img {
    
    width: 100%;
    
    position: fixed;
    
    bottom: 0;
    
    left: 0;
    
    }


### Explicação do CSS

- body: Define a fonte padrão, o tamanho da fonte, a cor do texto, margens e centraliza o texto.

- main: Define a largura e a margem da seção principal.

- h1: Define a fonte, cor e peso do título.

- h1 span: Adiciona negrito e cor ao texto dentro do span no título.

- #line: Define a linha de divisão com largura, altura e borda.

- .bold: Adiciona negrito e cor ao texto.

- footer a + a: Adiciona margem esquerda aos links no rodapé para espaçamento.

- a: Remove a decoração do texto dos links.

- footer img: Posiciona a imagem decorativa no rodapé.

  

## Conclusão

Neste projeto, o aprendizado envolveu a criação de uma página HTML básica e a aplicação de estilos CSS para melhorar a aparência do conteúdo. Utilizou-se o Google Fonts para importar fontes externas e garantir uma aparência mais profissional. O conhecimento adquirido pode ser expandido para criar páginas web mais complexas e interativas.