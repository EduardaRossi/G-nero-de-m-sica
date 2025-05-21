<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Favoritos</title>
</head>
<body>
    <center>
        <h1>🎧 Seu genero musical favorito 🎧</h1>
        <script>
            //criar uma variavel
            var opcao = parseInt(prompt(`Selecione a opção desejada
            1 - Rock'n'roll
            2 - Pop
            3 - Hip Hop
            4 - Eletronica
            5 - Jazz
            6 - Clásica`))
        switch(opcao) {
            case 1:
            document.write("É Rock 🎸")
            break;
            case 2:
            document.write("É POP 💋")
            break;
            case 3:
            document.write("É Hip Hop 🎤")
            break;
            case 4:
            document.write("É Eletronica 🎹")
            break;
            case 5:
            document.write("É Jazz 🎙")
            break;
            case 6:
            document.write("É Clássica 🎻")
            break;
            default:
            document.write("Opção inválida")
        }
        </script>
    </center>
</body>
</html>
