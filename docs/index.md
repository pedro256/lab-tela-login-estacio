<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,
initial-scale=1.0">
    <title>Estácio</title>
    <style>
        body {
            align-items: center;
            display: flex;
            flex-direction: row;
            flex-wrap: wrap;
        }

        .tela-login {
            border-radius: 5px;
            padding: 20px;
            width: 60%;
            background-color: #F3F5F6;
            margin: 0;
            position: absolute;
            top: 50%;
            left: 50%;
            margin-right: -50%;
            transform: translate(-50%, -50%)
        }

        .tela-login img {
            height: 50%;
        }

        .tela-login h4 {
            color: #57A3DC;
        }

        .formulario {
            padding: 15px;
            background-color: #ffff;
            border: rgb(189, 189, 189) 1px solid;
            border-top: #57A3DC 3px solid;
        }

        .grupo_input {
            align-items: center;
            display: flex;
            justify-content: space-between;
        }

        .grupo_input label {
            padding: 5px;
            width: 25%;
        }

        .grupo_input input {
            padding: 2px;
            padding-left: 5px;
            height: 30px;
            width: 75%;
            font-size: medium;
            border: rgb(189, 189, 189) 1px solid;
        }

        .checkbox-group {
            align-items: center;
            display: flex;
            padding-left: 5px;
            justify-content: space-between;
        }

        .checkbox-area {
            align-items: center;
            display: flex;
            width: 75%;
        }

        .checkbox-group .checkbox-area input {
            margin-right: 10px;
            height: 25px;
            width: 25px;
        }

        .button-group {
            padding: 10px;
            text-align: right;
            padding-right: 5px;
        }

        .button-group button {
            margin-right: 2px;
            padding: 10px;
            height: 40px;
        }

        #esqueci-senha {
            border: #E5E8E9 1px solid;
            background-color: #E5E8E9;
            color: #979797;
        }

        #entrar {
            border: #E5E8E9 1px solid;
            background-color: #76B8E4;
            color: #ffff;
        }
    </style>
</head>

<body>
    <div class='tela-login'>
        <img src="https://sia.estacio.br/sianet/Content/estacio/Images/Login/l
ogo-login.png">
        <h4>SIA - Sistema de Informações Acadêmicas</h4>
        <p>quarta-feira, 7 de outubro de 2020</p>
        <div class="formulario">
            <div class="grupo_input">
                <label>Matrícula</label><input type='text' placeholder="Digite sua matrícula">
            </div>
            <hr>
            <div class="grupo_input">
                <label>Senha</label><input type='password' placeholder="Digite sua Senha">
            </div>
            <hr>
            <div class="checkbox-group">
                <label>Verificação</label>
                <div class="checkbox-area">
                    <input type="checkbox">
                    <p>Não sou um robô</p>
                </div>
            </div>
        </div>
        <div class="button-group">
            <button id='esqueci-senha'>Esqueci minha
                senha</button><button id='entrar'>Entrar</button>
        </div>
    </div>
</body>

</html>
