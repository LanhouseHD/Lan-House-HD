# Lan-House-HD
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lan House HD</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap" rel="stylesheet">
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Montserrat', sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* Header */
        header {
            background: #1e3a8a;
            color: white;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            font-size: 1.8rem;
        }

        nav a {
            margin-left: 20px;
            font-weight: 600;
            transition: 0.3s;
        }

        nav a:hover {
            color: #facc15;
        }

        /* Banner */
        .banner {
            background: url('https://images.unsplash.com/photo-1581090700227-2f0b2146cde2?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzNjUyOXwwfDF8c2VhcmNofDJ8fGxhbiUyMGhvdXNlfGVufDB8fHx8MTY5MzUyODQ1Mw&ixlib=rb-4.0.3&q=80&w=1080') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }

        .banner h2 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        .banner p {
            font-size: 1.2rem;
        }

        /* Seção de serviços */
        section {
            padding: 50px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        section h2 {
            text-align: center;
            margin-bottom: 40px;
            color: #1e3a8a;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .service-card {
            background: #f3f4f6;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            transition: 0.3s;
        }

        .service-card:hover {
            background: #e0e7ff;
        }

        .service-card h3 {
            margin-bottom: 10px;
            color: #1e3a8a;
        }

        .service-card p {
            font-size: 0.95rem;
            margin-bottom: 15px;
        }

        .service-card button {
            background: #1e3a8a;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
            transition: 0.3s;
        }

        .service-card button:hover {
            background: #facc15;
            color: #1e3a8a;
        }

        /* Contato */
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            background: #f3f4f6;
            padding: 30px;
            border-radius: 10px;
        }

        .contact-form h3 {
            text-align: center;
            margin-bottom: 20px;
            color: #1e3a8a;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 12px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .contact-form button {
            width: 100%;
            background: #1e3a8a;
            color: white;
            border: none;
            padding: 12px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
            transition: 0.3s;
        }

        .contact-form button:hover {
            background: #facc15;
            color: #1e3a8a;
        }

        /* Footer */
        footer {
            background: #1e3a8a;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
        }

        @media (max-width: 768px) {
            header {
                flex-direction: column;
            }

            nav a {
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>Lan House HD</h1>
        <nav>
            <a href="#services">Serviços</a>
            <a href="#contact">Contato</a>
            <a href="#about">Sobre nós</a>
        </nav>
    </header>

    <!-- Banner -->
    <div class="banner">
        <h2>Bem-vindo à Lan House HD</h2>
        <p>Serviços de Xerox, Impressão, Digitalização e muito mais!</p>
    </div>

    <!-- Serviços -->
    <section id="services">
        <h2>Nossos Serviços</h2>
        <div class="services-grid">
            <!-- Escritório -->
            <div class="service-card">
                <h3>Xerox</h3>
                <p>Copias rápidas e com alta qualidade.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>Impressão</h3>
                <p>Impressão de documentos e trabalhos diversos.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>Escaneamento</h3>
                <p>Digitalize seus documentos facilmente.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>Enviar E-mail</h3>
                <p>Envio de documentos diretamente do nosso computador.</p>
                <button>Solicitar</button>
            </div>

            <!-- Documentos -->
            <div class="service-card">
                <h3>Antecedentes Criminais</h3>
                <p>Emita seu certificado com facilidade.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>Quitação Eleitoral</h3>
                <p>Regularize sua situação eleitoral.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>Criar E-mail</h3>
                <p>Criação de contas de e-mail profissionais.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>Cadastro</h3>
                <p>Auxílio para cadastros em sites e órgãos.</p>
                <button>Solicitar</button>
            </div>

            <!-- DETRAN / Veículos -->
            <div class="service-card">
                <h3>DETRAN</h3>
                <p>Consultas, renovação e serviços de CNH.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>MEU INSS</h3>
                <p>Auxílio para acesso e serviços do INSS.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>Curriculum</h3>
                <p>Criação e edição de currículos profissionais.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>Boletim de Ocorrência</h3>
                <p>Registro rápido e seguro de ocorrências.</p>
                <button>Solicitar</button>
            </div>

            <div class="service-card">
                <h3>Renovação CNH</h3>
                <p>Auxílio completo para renovação de CNH.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>Agendamento Geral</h3>
                <p>Agende serviços em órgãos públicos.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>Contrato Aluguel</h3>
                <p>Criação e impressão de contratos de aluguel.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>Digitação por Folha</h3>
                <p>Transcrição de documentos para formato digital.</p>
                <button>Solicitar</button>
            </div>

            <div class="service-card">
                <h3>Consulta SPC/SERASA/CARTORIO</h3>
                <p>Verifique sua situação financeira rapidamente.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>Consulta Básica Carro</h3>
                <p>Informações essenciais sobre veículos.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>Consulta Plus Carro</h3>
                <p>Informações detalhadas sobre veículos.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>Consulta Total Carro</h3>
                <p>Relatório completo de veículos.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>Transferência Veicular</h3>
                <p>Auxílio na transferência de propriedade.</p>
                <button>Solicitar</button>
            </div>
            <div class="service-card">
                <h3>Transferir Multa</h3>
                <p>Procedimento para transferência de multas de veículos.</p>
                <button>Solicitar</button>
            </div>
        </div>
    </section>

    <!-- Contato -->
    <section id="contact">
        <div class="contact-form">
            <h3>Entre em Contato</h3>
            <form>
                <input type="text" placeholder="Nome" required>
                <input type="email" placeholder="Email" required>
                <input type="tel" placeholder="Telefone" required>
                <input type="text" placeholder="Serviço desejado" required>
                <textarea rows="5" placeholder="Mensagem"></textarea>
                <button type="submit">Enviar Mensagem</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Lan House HD. Todos os direitos reservados.</p>
        <p>Endereço, Telefone, WhatsApp</p>
    </footer>

</body>
</html>
