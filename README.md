# Portf-lio-em-CSS
# Portf-lio-em-CSS
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #0f172a;
            color: #f1f5f9;
        }

        header {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(90deg, #1e293b, #334155);
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 20px;
            display: grid;
            gap: 20px;
        }

        .card {
            background: #1e293b;
            padding: 20px;
            border-radius: 16px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
        }

        .profile {
            display: flex;
            align-items: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .profile img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #38bdf8;
        }

        .info h2 {
            margin: 0 0 10px;
        }

        footer {
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            background: #1e293b;
            font-size: 0.9rem;
            color: #94a3b8;
        }

        .highlight {
            color: #38bdf8;
            font-weight: bold;
        }
    </style>
</head>
<body>

<header>
    <h1>Matheus Penna</h1>
    <p>Meu Portfólio Pessoal</p>
</header>

<div class="container">

    <div class="card profile">
        <img src="file:///C:/Users/mathe/OneDrive/Imagens/Saved%20Pictures/8b4f3288-fc19-421c-8a15-03c2fbadaf94.jpg" alt="Minha Foto">
        <div class="info">
            <h2>Sobre mim</h2>
            <p>Tenho <span class="highlight">17 anos</span> e sou estudante de <span class="highlight">Engenharia da Computação</span>.</p>
            <p>Quero aprender a programar para meu desenvolvimento na carreira.</p>
        </div>
    </div>

    <div class="card">
        <h2>Interesses</h2>
        <p><span class="highlight">Futebol/Basquete </span> </p>
        <p><span class="highlight">Flamengo</span> 🔴⚫</p>
    </div>

    <div class="card">
        <h2>Contato</h2>
        <p>Email:matheuspenna.2009@gmail.com</p>
    </div>

</div>

<footer>
    <p>© 2026 - Matheus Penna. Todos os direitos reservados.</p>
</footer>

</body>
</html>
