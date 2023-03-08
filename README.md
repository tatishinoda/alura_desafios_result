# Alura Dev Front-End | Respostas dos Desafios

Projeto base para as respostas dos desafios propostos.

## Iniciando

Crie sua branch com as respostas para os desafios.

## Organização das pastas

Para um melhor entendimento irei propor a seguinte organização:
`tipo de projeto > número do desafio > arquivos`. Mas para entender melhor, aqui está um esquema:

```
► 📁 php
► 📁 css
▼ 📁 js
    ▼ 📁 01
        📄 index.html
    ▼ 📁 02
        📄 index.html
```

## Template
Nesse projeto já tem um template html usando o [Bootstrap](https://getbootstrap.com/) para termos um melhor entendimento dos elementos durante os desafios.

Mas aqui está a base também:
```html
<!doctype html>
<html lang="pt-br">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">

    <title>Resposta do Desafio - 01</title>
</head>

<body>
    <div class="container py-5">

        <style>
            /* Caso queira algum estilo adicional */
        </style>

        <h1>Olá mundo!</h1>

        <script>
            // Código JS aqui
        </script>

    </div>
</body>

</html>
```

Note que deixei já separado o lugar de usar CSS, a área de usar o HTML e em seguida o JS. Só precisa usar o que for necessário. Em alguns desafios de CSS ireimos desativar o [Bootstrap](https://getbootstrap.com/).

## Live Preview

Recomendo usar o [VSCode](https://code.visualstudio.com/) junto da extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).

![Live Server](https://github.com/ritwickdey/vscode-live-server/raw/HEAD/images/Screenshot/vscode-live-server-animated-demo.gif)

Caso queiram usar o **IntelliJ IDEA**, encontrei um vídeo que ensina como ativar o preview para HTML, CSS e JS:

[![Live Edit HTML & CSS in 60 Seconds](https://img.youtube.com/vi/xf90Ko64hRc/0.jpg)](https://www.youtube.com/watch?v=xf90Ko64hRc)
