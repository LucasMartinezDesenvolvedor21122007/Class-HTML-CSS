<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="index.css" media="Screen">
    <title>Cadastro</title>
</head>
<script type="text/javascript" src="index.js"></script>
<body>
    <div class="campo">
        <h1 id="titulo">Cadastro De DEVs</h1>
        <p id="subtitulo">Complete suas informações</p>
        <br>
    </div class="campo">

    <form>
        <fieldset class="Grupo">
            <div class="campo">
                <label for="nome"><strong>Nome</strong></label>
                <input type="text" name="Nome" id="Nome" required>
            </div class="campo">

            <div class="campo">
                <label for="Sobrenome"><strong>Sobrenome</strong></label>
                <input type="text" name="Sobrenome" id="Sobrenome" required>
            </div class="campo">

            <div class="Campo">
                <label for="Email"><strong>Email</strong></label>
                <input type="email" name="email" id="email" required>
            </div class="campo">
        </fieldset class="Grupo">
<br>
    <div class="Campo">
        <label><strong>De Qual Lado Da Aplicação Você Desenvolve</strong></label>
        <label>
            <input type="radio" name="devweb" value="Front-End">Front-End
        </label>
        <label>
            <input type="radio" name="devweb" value="Back-End">Back-End
        </label>
        <label>
            <input type="radio" name="devweb" value="Fullstack">Fullstack
        </label>
    </div class="campo">
    
<div class="Campo">
    <label for="senioridade">Senioridade</label>
    <select id="senioridade">
        <option selected disabled value="">Escolha</option>
        <option>Junior</option>
        <option>Pleno</option>
        <option>Sênior</option>
    </select>
</div class="campo">

<fieldset class="Grupo">
    <div id="check">
        <label><strong>Selecione as Tecnologias Que Utiliza</strong></label><br><br>
        <input type="checkbox" name="tecnologia1" id="tecnologia1" value="HTML">
        <label for="tecnologia1">HTML</label>
        <input type="checkbox" name="tecnologia2" id="tecnologia2" value="CSS">
        <label for="tecnologia2">CSS</label>
        <input type="checkbox" name="tecnologia3" id="tecnologia3" value="Javascript">
        <label for="tecnologia3">Javascript</label>
        <input type="checkbox" name="tecnologia4" id="tecnologia4" value="PHP">
        <label for="tecnologia4">PHP</label>
        <input type="checkbox" name="tecnologia5" id="tecnologia5" value="C#">
        <label for="tecnologia5">C#</label>
        <input type="checkbox" name="tecnologia6" id="tecnologia6" value="Python">
        <label for="tecnologia6">Python</label>
    </div class="campo">
</fieldset class="Grupo">
</form>

<div class="campo">
    <br>
    <label><strong></strong>Conte Um Pouco Da Sua Experiência</strong></label>
    <textarea row="6" style="width:26em" id="experiência" name="Experiência"></textarea>
</div class="campo">

<button class="Botão" type="submit">Concluido</button>

</body>
</html>

*{
    margin:0;
    padding:0;
}

#titulo{
    font-family: sans-serif;
    Color:#380b61;
    margin-left:7%;
}
#subtitulo{
    font-family: sans-serif;
    Color:#380b61;
    margin-left:10%;
}

fieldset{
    Border:0;
}

body{
    background-color:#F0F8FF;
    font-family:sans-serif;
    font-size:1em;
    color:#59429d;
    margin-left: 36%;
    margin-top: 2%;
    justify-content: center;
}

input, select, textarea, button{
    border-radius: 5px;
}

.campo{
    margin-bottom: 1em;
}

.campo Label{
    margin-bottom: 0.2em;
    Color:#59429d;
    Display:Block;
}

fieldset.grupo .campo{
    float:left;
    margin-right: 2em;
}

.campo input [type="text"], .campo input[type="email"], .campo select, .campo textarea{
    Padding:0.2em;
    border:1px solid #59429d;
    box-shadow: 2px 2px 2px rgba(0,0,0,0.2);
    Display:Block;
}

.campo select option{
    padding-right: 1em;
}

.campo input:focus, .campo select:focus, .campo textarea:focus{
    background:#E0E0F8;
}

.botão{
    font-size: 1.2em;
    background: #59429d;
    border:0;
    margin-bottom: 1em;
    color:#ffff;
    padding:0.2em, 0.6em;
    box-shadow: 2px 2px 2px rgba(0,0,0,0.2);
    text-shadow: 1px, 1px, 1px rgba(0,0,0,0.5);
    position:absolute;
    top:90%;
    left:50%;
    margin-right: -50%;
    transform:translate(-50%,-50%)
}

.botão:hover{
    background-color: #ccbbff;
    box-shadow: inset 2px 2px 2px 2px rgba(0,0,0,0.2);
    text-shadow: none;
}

#check{
    display:inline-block;
}
