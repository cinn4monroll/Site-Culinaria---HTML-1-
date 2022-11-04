# Site-Culinaria---HTML-1-
Trabalho pensamento computacional - Prof. André Ribas

Link do site :
file:///C:/Users/ACER/Desktop/trabalhos%20-%20gaby/index.html

Código :

index.html;

<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <title>Curso de Culinária</title>
        <link rel="stylesheet" href="style.css">
    </head>

    <body>
        <header>
            <h1 class="titulo-principal">Curso de Culinária</h1>
        </header>
        
        <img src="imagemculinariabanner.jpg" class="cabecalho"> 
        
        <div class="principal">
            <h2 class="titulo-centralizado">Sobre o Curso de Culinária</h2>
        
            <p class="aumentar">Localizada no coração de Curitiba o <strong>Curso de Culinária</strong> traz para o mercado o que há de melhor para o seu paladar e aprendizado. 
            Fundada em 2022, o Curso de Culinária já é destaque na cidade e conquista novos interessados a cada dia.</p>
        
            <p id="missao"><em>Nossa missão é: <strong>"Proporcionar ensino de qualidade e receitas de todo tipo"</strong>.</em></p>
        
            <p class="aumentar">Oferecemos profissionais experientes e antenados às mudanças no mundo da gastronomia. 
            O ensino possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos estudantes.</p>
        </div>

        <div class="beneficios">
            <h3 class="titulo-centralizado" >Benefícios </h3>
        
            <ul>
                <li class="itens">Desenvolvimento de criatividade mas sem sair do tradicional da comida</li>
                <li class="itens">Espaço acolhedor e confortável para inovar</li>
                <li class="itens">Central em relação de Curitiba</li>
                <li class="itens">Profissionais Qualificados e animados para ensinar</li>
            </ul>
        
            <img src="imagemculinaria.jpg" class="imagemculinaria">
        </div>

        style.css;
      
      body {
    background: #ffffff;
}

.cabecalho {
    width: 100%;
}

h1 {
    text-align: center
}

p {
    text-align: center;
}

#missao {
    font-size: 30px
}

em strong {
    color: #da646e;
}

body {
    
    
    background: #ffffff;
    padding: 30px; 
}

.itens {
    font-style: italic;
}

.beneficios {
    background: #f8a1a1;
    padding: 20px;
}

h2 {
    text-align: center;
}

ul {
    display: inline-block;
    vertical-align: top;
    width: 20%;
    margin-right: 15%;
}

.imagemculinaria {
    width: 50%;
}

.titulo-principal {
    padding-left: 80px;
}

.titulo-centralizado {
    text-align: center
}

.aumentar {
    font-size: 20pt;
}
