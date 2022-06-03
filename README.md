# Web-app-do-Devando01

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Estilo/pagprincipal.css">
    <script src="Banco de Dados/Database.js"></script>
    <title>Pág Principal</title>
</head>
<body>
    <div class="container1">
        <header>
            <h1 id="titulo">nano scheduling</h1>
        </header>
        <nav>
            <div id="Nav-bar-menu">
            <ul>
                <li>
                    <a href="">
                    <img src="imagens/icones-menu/menu-hamburguer (1).png" alt="Menu-hamburguer" class="icone-menu" style="margin-top: -200px;" id="amburguer">
                    </a>
                </li>
                <li>
                    <a href="">
                    <img src="imagens/do-utilizador.png" alt="" class="icone-menu" id="icone-perfil">
                    <p class="text-menu">Seu perfil</p>
                    </a>
                </li>
                <li>
                    <a href="">
                    <img src="imagens/icones-menu/configuracoes.png" alt="Configurações" class="icone-menu" id="icone-configuracoes">
                    <p class="text-menu">Configurações</p>

                    </a>

                </li>
                <li>

                    <a href="">
                    <img src="imagens/icones-menu/suporte-ao-cliente.png" alt="Fale Com Os Desenvolvedores" class="icone-menu" id="icone-suporte">
                    <p class="text-menu">Fale com os Desenvolvedores</p>
                    </a>

                </li>
            </ul>
            </div>
        </nav>
        <main>

            <section> 

                <form action="">
                    <fieldset>
                        <legend>Agendamento</legend>
                        <Label for="Item"> <b>Item </b></Label>
                        <select name="Item" id="Item" class="inputs" required>
                            <option value="0">Selecione</option>
                            <option value="Data_Show">Data Show</option>
                            <option value="Tv">TV</option>
                            <option value="Projetor">Projetor</option>
                        </select>

                        <label for="Data">Data do Agendamento</label>
                        <input type="date" name="Data-agendamento" id="Data"  max="01-01-2023" min="01-05-2022" class="inputs" required>
                        <label for="AulaData">Escolha a Aula</label>
                        <select name="Aula" id="AulaData" class="inputs" required>
                            <option value="0">Selecione a Aula</option>
                            <option value="1">Aula 1</option>
                            <option value="2">Aula 2</option>
                            <option value="3">Aula 3</option>
                            <option value="4">Aula 4</option>
                            <option value="5">Aula 5</option>
                            <option value="6">Aula 6</option>
                            <option value="7">Aula 7</option>
                            <option value="8">Aula 8</option>
                            <option value="9">Aula 9</option>
                        </select>
                        <input type="submit" value="Marcar Seu item" class="inputs" id="submit">
                    </fieldset>
                </form>

        </section>

        </main>
    </div>
</body>
</html>
