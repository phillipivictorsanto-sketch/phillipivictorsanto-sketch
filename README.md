<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio - GitHub</title>
    <style>
        body {
            background-color: rgb(136, 0, 255);
            color: white;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            text-align: center;
            margin-bottom: 40px;
        }

        h1 {
            color: rgb(17, 253, 0);
            font-size: 2.5rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        h2 {
            color: rgb(255, 230, 0);
        }

        .subtitulo {
            color: rgb(255, 255, 255);
            font-size: 1.2rem;
            font-weight: bold;
            background-color: rgba(0, 0, 0, 0.3);
            padding: 10px 20px;
            border-radius: 20px;
        }

        .container {
            max-width: 800px;
            width: 100%;
            background: rgba(255, 255, 255, 0.1);
            padding: 30px;
            border-radius: 15px;
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.3);
        }

        .tags {
            display: flex;
            gap: 10px;
            justify-content: center;
            flex-wrap: wrap;
            margin-bottom: 30px;
        }

        .tag {
            background-color: rgb(17, 253, 0);
            color: black;
            padding: 8px 15px;
            border-radius: 5px;
            font-weight: bold;
            font-size: 0.9rem;
        }

        .section-title {
            border-bottom: 2px solid rgb(17, 253, 0);
            padding-bottom: 10px;
            margin-top: 30px;
        }

        .grid-prototipos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .card {
            background: rgba(0, 0, 0, 0.4);
            border: 1px solid rgb(17, 253, 0);
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .btn {
            display: inline-block;
            background-color: rgb(255, 0, 0);
            color: white;
            text-decoration: none;
            padding: 8px 16px;
            border-radius: 4px;
            margin-top: 15px;
            font-weight: bold;
        }

        .btn:hover {
            background-color: rgb(200, 0, 0);
        }
    </style>
</head>
<body>

    <header>
        <h1>Violão é muito bom! Teste no GitHub</h1>
        <p class="subtitulo">Bem-vindo ao melhor site do século 🚀</p>
    </header>

    <div class="container">
        <div class="tags">
            <span class="tag">📚 Estudante de Programação</span>
            <span class="tag">🎨 Designer</span>
            <span class="tag">💻 Front-End</span>
        </div>

        <section>
            <h2 class="section-title">Sobre Mim</h2>
            <p>Olá! Sou apaixonado por tecnologia, música (principalmente violão!) e por criar interfaces incríveis. Estou unindo o mundo do design com o desenvolvimento front-end para construir experiências digitais únicas.</p>
        </section>

        <section>
            <h2 class="section-title">Meus Protótipos & Projetos</h2>
            <div class="grid-prototipos">
                
                <div class="card">
                    <h3>Protótipo Violão App</h3>
                    <p>Design de interface e ideias para um afinador ou cifrador de violão moderno.</p>
                    <a href="#" class="btn">Ver Projeto</a>
                </div>

                <div class="card">
                    <h3>Site do Século V1</h3>
                    <p>A primeira versão deste site incrível feito com HTML e CSS puro.</p>
                    <a href="#" class="btn">Ver Projeto</a>
                </div>

                <div class="card">
                    <h3>Portfólio UI</h3>
                    <p>Conceito visual criado no Figma para o meu futuro portfólio.</p>
                    <a href="#" class="btn">Ver Projeto</a>
                </div>

            </div>
        </section>
    </div>

</body>
</html>
