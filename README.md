```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Caio Ribeiro - História e Carreira</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: #07111f;
            color: #ffffff;
            line-height: 1.6;
        }

        /* CABEÇALHO */
        header {
            min-height: 430px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 50px 20px;
            background:
                radial-gradient(circle at top, #16547d 0%, #0a1b2e 45%, #07111f 80%);
        }

        .header-content {
            max-width: 850px;
        }

        .badge {
            display: inline-block;
            padding: 8px 18px;
            border: 1px solid #4ca8d8;
            border-radius: 30px;
            color: #69d5ff;
            font-size: 14px;
            font-weight: bold;
            margin-bottom: 20px;
        }

        header h1 {
            font-size: clamp(45px, 8vw, 85px);
            margin-bottom: 10px;
        }

        header p {
            color: #b7c7d8;
            font-size: 18px;
            max-width: 750px;
            margin: auto;
        }

        /* MENU */
        nav {
            position: sticky;
            top: 0;
            z-index: 100;
            background: rgba(5, 15, 27, 0.95);
            border-bottom: 1px solid #24415e;
            backdrop-filter: blur(10px);
        }

        .menu {
            max-width: 1100px;
            margin: auto;
            display: flex;
            justify-content: center;
            gap: 8px;
            padding: 12px;
            overflow-x: auto;
        }

        .menu button {
            border: 1px solid transparent;
            background: transparent;
            color: #a9b8ca;
            padding: 11px 18px;
            border-radius: 10px;
            cursor: pointer;
            font-weight: bold;
            white-space: nowrap;
            transition: 0.3s;
        }

        .menu button:hover,
        .menu button.active {
            background: #122842;
            color: #ffffff;
            border-color: #2b6288;
        }

        /* CONTEÚDO */
        main {
            max-width: 1100px;
            margin: auto;
            padding: 45px 20px;
        }

        section {
            display: none;
            animation: aparecer 0.35s ease;
        }

        section.active {
            display: block;
        }

        @keyframes aparecer {
            from {
                opacity: 0;
                transform: translateY(15px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        section h2 {
            font-size: 35px;
            margin-bottom: 25px;
        }

        /* CARDS */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 18px;
        }

        .card {
            background: linear-gradient(145deg, #0e1d30, #0a1829);
            border: 1px solid #24415e;
            border-radius: 18px;
            padding: 25px;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
            border-color: #318fc3;
        }

        .card h3 {
            color: #67d4ff;
            margin-bottom: 10px;
        }

        .card p {
            color: #c3d0dd;
        }

        .numero {
            font-size: 34px;
            font-weight: bold;
            color: #ffffff;
        }

        .descricao {
            color: #8fa5ba;
            font-size: 14px;
        }

        .espaco {
            margin-top: 20px;
        }

        /* LINHA DO TEMPO */
        .timeline {
            border-left: 3px solid #299ed5;
            padding-left: 30px;
            margin-left: 10px;
        }

        .evento {
            position: relative;
            margin-bottom: 35px;
        }

        .evento::before {
            content: "";
            position: absolute;
            left: -40px;
            top: 5px;
            width: 14px;
            height: 14px;
            background: #35b7ef;
            border-radius: 50%;
            box-shadow: 0 0 0 5px #0b2136;
        }

        .ano {
            color: #67d4ff;
            font-weight: bold;
            font-size: 17px;
        }

        .clube {
            font-size: 22px;
            font-weight: bold;
            margin: 3px 0;
        }

        /* TABELA */
        .tabela-container {
            overflow-x: auto;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            background: #0e1d30;
            border-radius: 15px;
            overflow: hidden;
        }

        th,
        td {
            padding: 15px;
            border-bottom: 1px solid #24415e;
            text-align: left;
        }

        th {
            background: #122842;
            color: #69d5ff;
        }

        td {
            color: #d1dce7;
        }

        /* DESTAQUE */
        .destaque {
            border-left: 5px solid #35b7ef;
            padding: 15px 20px;
            margin-top: 20px;
            background: #0d2034;
            font-size: 19px;
            color: #dbe8f4;
        }

        /* RODAPÉ */
        footer {
            text-align: center;
            padding: 40px 20px;
            margin-top: 30px;
            border-top: 1px solid #24415e;
            color: #8fa5ba;
        }

        /* RESPONSIVO */
        @media (max-width: 600px) {

            header {
                min-height: 380px;
            }

            header h1 {
                font-size: 48px;
            }

            header p {
                font-size: 16px;
            }

            main {
                padding: 30px 15px;
            }

            section h2 {
                font-size: 28px;
            }

            .card {
                padding: 20px;
            }

            .menu {
                justify-content: flex-start;
            }
        }
    </style>
</head>

<body>

    <!-- CABEÇALHO -->
    <header>

        <div class="header-content">

            <span class="badge">
                HISTÓRIA DO FUTEBOL BRASILEIRO
            </span>

            <h1>
                Caio Ribeiro
            </h1>

            <p>
                A trajetória do ex-atacante brasileiro que começou
                no São Paulo, passou pelo futebol europeu, vestiu
                a camisa da Seleção Brasileira e depois construiu
                uma carreira na comunicação esportiva.
            </p>

        </div>

    </header>


    <!-- MENU -->
    <nav>

        <div class="menu">

            <button
                class="active"
                onclick="mostrarPagina('inicio', this)">
                🏠 Início
            </button>

            <button
                onclick="mostrarPagina('biografia', this)">
                📖 Biografia
            </button>

            <button
                onclick="mostrarPagina('carreira', this)">
                ⚽ Carreira
            </button>

            <button
                onclick="mostrarPagina('selecao', this)">
                🇧🇷 Seleção
            </button>

            <button
                onclick="mostrarPagina('titulos', this)">
                🏆 Títulos
            </button>

            <button
                onclick="mostrarPagina('pos-carreira', this)">
                🎙️ Depois dos gramados
            </button>

            <button
                onclick="mostrarPagina('fontes', this)">
                📚 Fontes
            </button>

        </div>

    </nav>


    <!-- CONTEÚDO -->
    <main>


        <!-- INÍCIO -->
        <section id="inicio" class="active">

            <div class="grid">

                <div class="card">
                    <div class="numero">1975</div>
                    <div class="descricao">
                        Ano de nascimento
                    </div>

                    <p>
                        Caio Ribeiro Decoussau nasceu em São Paulo,
                        no dia 16 de agosto de 1975.
                    </p>
                </div>


                <div class="card">
                    <div class="numero">Atacante</div>

                    <div class="descricao">
                        Posição
                    </div>

                    <p>
                        Durante sua carreira, Caio atuou
                        principalmente como atacante.
                    </p>
                </div>


                <div class="card">
                    <div class="numero">São Paulo</div>

                    <div class="descricao">
                        Clube de formação
                    </div>

                    <p>
                        Foi formado nas categorias de base
                        do São Paulo Futebol Clube.
                    </p>
                </div>


                <div class="card">
                    <div class="numero">Europa</div>

                    <div class="descricao">
                        Experiência internacional
                    </div>

                    <p>
                        Jogou na Itália por Internazionale
                        e Napoli.
                    </p>
                </div>

            </div>


            <div class="card espaco">

                <h2>
                    Quem foi Caio Ribeiro?
                </h2>

                <p>
                    Caio Ribeiro foi um atacante brasileiro
                    que ganhou destaque ainda jovem.
                    Revelado pelo São Paulo, chamou atenção
                    por seu desempenho nas categorias de base
                    e chegou rapidamente ao futebol profissional.
                </p>

                <br>

                <p>
                    Depois de atuar pelo São Paulo, Caio teve
                    experiências no futebol europeu e retornou
                    ao Brasil, defendendo diversos clubes.
                </p>

                <br>

                <p>
                    Após encerrar sua carreira como jogador,
                    iniciou uma nova trajetória na comunicação
                    esportiva, tornando-se conhecido como
                    comentarista de futebol.
                </p>

            </div>

        </section>


        <!-- BIOGRAFIA -->
        <section id="biografia">

            <h2>
                📖 Biografia
            </h2>

            <div class="card">

                <p>
                    Caio Ribeiro Decoussau nasceu em São Paulo,
                    em 16 de agosto de 1975.
                </p>

                <br>

                <p>
                    Desde jovem, esteve ligado ao futebol.
                    Desenvolveu-se nas categorias de base do
                    São Paulo e passou a ser considerado uma
                    promessa do futebol brasileiro.
                </p>

                <br>

                <p>
                    Sua ascensão foi rápida. Além de defender
                    o São Paulo profissionalmente, Caio também
                    participou de seleções brasileiras de base.
                </p>

                <br>

                <p>
                    O bom desempenho fez com que recebesse
                    oportunidades no futebol europeu.
                </p>

                <div class="destaque">

                    "A carreira de Caio Ribeiro é marcada
                    pela passagem do campo para a televisão,
                    mantendo sua ligação com o futebol."

                </div>

            </div>

        </section>


        <!-- CARREIRA -->
        <section id="carreira">

            <h2>
                ⚽ Carreira
            </h2>

            <div class="timeline">


                <div class="evento">

                    <div class="ano">
                        Início dos anos 1990
                    </div>

                    <div class="clube">
                        São Paulo
                    </div>

                    <p>
                        Caio surgiu nas categorias de base
                        do São Paulo e chegou ao futebol
                        profissional ainda jovem.
                    </p>

                </div>


                <div class="evento">

                    <div class="ano">
                        1995–1996
                    </div>

                    <div class="clube">
                        Internazionale
                    </div>

                    <p>
                        Depois de se destacar nas categorias
                        de base da Seleção Brasileira, Caio
                        foi contratado pela Internazionale,
                        da Itália.
                    </p>

                </div>


                <div class="evento">

                    <div class="ano">
                        1996–1997
                    </div>

                    <div class="clube">
                        Napoli
                    </div>

                    <p>
                        Atuou pelo Napoli durante sua passagem
                        pelo futebol italiano.
                    </p>

                </div>


                <div class="evento">

                    <div class="ano">
                        1997
                    </div>

                    <div class="clube">
                        Santos
                    </div>

                    <p>
                        Retornou ao Brasil e defendeu o Santos,
                        conquistando o Torneio Rio-São Paulo.
                    </p>

                </div>


                <div class="evento">

                    <div class="ano">
                        1998–1999
                    </div>

                    <div class="clube">
                        Flamengo
                    </div>

                    <p>
                        Teve uma passagem de destaque pelo
                        Flamengo e ganhou reconhecimento
                        entre os torcedores.
                    </p>

                </div>


                <div class="evento">

                    <div class="ano">
                        2000–2004
                    </div>

                    <div class="clube">
                        Diversos clubes
                    </div>

                    <p>
                        Ao longo desses anos, Caio passou por
                        Santos, Fluminense, Flamengo, Grêmio
                        e também pelo futebol alemão.
                    </p>

                </div>


                <div class="evento">

                    <div class="ano">
                        2004–2005
                    </div>

                    <div class="clube">
                        Botafogo
                    </div>

                    <p>
                        O Botafogo foi seu último clube
                        profissional. Caio encerrou sua
                        carreira como jogador aos 30 anos.
                    </p>

                </div>

            </div>

        </section>


        <!-- SELEÇÃO -->
        <section id="selecao">

            <h2>
                🇧🇷 Seleção Brasileira
            </h2>

            <div class="grid">


                <div class="card">

                    <h3>
                        Seleção Sub-20
                    </h3>

                    <p>
                        Caio participou da Seleção Brasileira
                        Sub-20 e ganhou destaque durante o
                        Mundial da categoria em 1995.
                    </p>

                </div>


                <div class="card">

                    <h3>
                        Seleção Principal
                    </h3>

                    <p>
                        O atacante também recebeu oportunidades
                        na Seleção Brasileira principal durante
                        a década de 1990.
                    </p>

                </div>


                <div class="card">

                    <h3>
                        Reconhecimento
                    </h3>

                    <p>
                        Sua participação nas seleções de base
                        ajudou a aumentar sua visibilidade e
                        contribuiu para sua transferência para
                        o futebol europeu.
                    </p>

                </div>

            </div>

        </section>


        <!-- TÍTULOS -->
        <section id="titulos">

            <h2>
                🏆 Títulos e conquistas
            </h2>

            <div class="tabela-container">

                <table>

                    <thead>

                        <tr>
                            <th>Ano</th>
                            <th>Conquista</th>
                            <th>Clube / Seleção</th>
                        </tr>

                    </thead>

                    <tbody>

                        <tr>
                            <td>1994</td>
                            <td>Recopa Sul-Americana</td>
                            <td>São Paulo</td>
                        </tr>

                        <tr>
                            <td>1994</td>
                            <td>Copa CONMEBOL</td>
                            <td>São Paulo</td>
                        </tr>

                        <tr>
                            <td>1997</td>
                            <td>Torneio Rio-São Paulo</td>
                            <td>Santos</td>
                        </tr>

                        <tr>
                            <td>1999</td>
                            <td>Copa Mercosul</td>
                            <td>Flamengo</td>
                        </tr>

                    </tbody>

                </table>

            </div>

        </section>


        <!-- PÓS CARREIRA -->
        <section id="pos-carreira">

            <h2>
                🎙️ Depois dos gramados
            </h2>

            <div class="card">

                <p>
                    Depois de encerrar sua carreira como
                    jogador profissional, Caio Ribeiro
                    iniciou uma nova etapa profissional.
                </p>

                <br>

                <p>
                    Ele estudou Gestão do Esporte e passou
                    a trabalhar na comunicação esportiva.
                </p>

                <br>

                <p>
                    Como comentarista, passou a participar
                    de transmissões e programas relacionados
                    ao futebol.
                </p>

                <br>

                <p>
                    Dessa maneira, continuou ligado ao esporte,
                    agora analisando as partidas e compartilhando
                    sua experiência com o público.
                </p>

                <div class="destaque">

                    Do jogador dentro das quatro linhas
                    ao comentarista diante das câmeras.

                </div>

            </div>

        </section>


        <!-- FONTES -->
        <section id="fontes">

            <h2>
                📚 Fontes
            </h2>

            <div class="card">

                <h3>
                    São Paulo Futebol Clube
                </h3>

                <p>
                    Informações históricas sobre a passagem
                    de Caio pelo clube.
                </p>

                <br>

                <h3>
                    Terceiro Tempo
                </h3>

                <p>
                    Dados biográficos e informações sobre
                    a carreira do jogador.
                </p>

                <br>

                <h3>
                    UOL
                </h3>

                <p>
                    Informações biográficas e profissionais.
                </p>

                <br>

                <p>
                    Este site foi elaborado para fins
                    educativos, reunindo e organizando
                    informações sobre a trajetória de
                    Caio Ribeiro.
                </p>

            </div>

        </section>

    </main>


    <!-- RODAPÉ -->
    <footer>

        <p>
            ⚽ História de Caio Ribeiro
        </p>

        <p>
            Site educativo • HTML + CSS + JavaScript
        </p>

    </footer>


    <!-- JAVASCRIPT -->
    <script>

        function mostrarPagina(pagina, botao) {

            // Esconde todas as seções
            const secoes = document.querySelectorAll("section");

            secoes.forEach(function(secao) {
                secao.classList.remove("active");
            });


            // Mostra a seção escolhida
            document
                .getElementById(pagina)
                .classList.add("active");


            // Remove o destaque de todos os botões
            const botoes = document.querySelectorAll(".menu button");

            botoes.forEach(function(botaoMenu) {
                botaoMenu.classList.remove("active");
            });


            // Destaca o botão selecionado
            botao.classList.add("active");


            // Volta para o topo
            window.scrollTo({
                top: 0,
                behavior: "smooth"
            });

        }

    </script>

</body>
</html>
```
