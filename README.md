# TRABALHANDO COM FORMULÁRIOS EM HTML
#### Conecte-se comigo
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/isadora-mendes-3b8605336/)
[![Instagram](https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/neves_azure/)

#### Linguagens de Marcação e Estilo que estou aprendendo
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000?style=for-the-badge&logo=markdown)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Visão geral de um formulário no HTML

```
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trabalhando com formulários em HTML</title>
</head>
<body>
    <form action="#" name="Cadastro" method="post" target="_blank" autocomplete="off" onsubmit="alert('Formulário enviado com sucesso')">
        Nome:<input type="text" name="Nome"/><br>
        Idade:<input type="number" name="Idade"/><br>
        Senha: <input type="password" name="Senha"/><br>
        <button type="submit">Enviar</button>
    </form>
</body>
</html>
```
## Alguns tipos de inputs
```
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trabalhando com formulários em HTML</title>
</head>
<body>
    <form action="">
        <label for="">Text</label><input type="text"/><br>
        <label for="">Number</label><input type="number" min="0" max="99" step="5"/><br>
        <label for="">Button</label><input type="button" value="Enviar"/><br>
        <label for="">Range</label><input type="range"><br>
        <label for="">Radio</label><input type="radio" name="rad"><label for=""></label><input type="radio" name="rad"><br>
    </form>
</body>
</html>
```
## Radio e Checkbox
```
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trabalhando com formulários em HTML</title>
</head>
<body>
    <form action="" method="post">
        <h3>Você tem geladeira em casa?</h3>
        <input type="radio" name="geladeira" value="sim">Sim<br>
        <input type="radio" name="geladeira" value="nao">Não<br>
        <h3>Quais itens você tem?</h3>
        <input type="checkbox" name="itens[]" value="computador">Computador<br>
        <input type="checkbox" name="itens[]" value="celular">Celular<br>
        <input type="checkbox" name="itens[]" value="rádio">Rádio<br>

    </form>
</body>
</html>
```
