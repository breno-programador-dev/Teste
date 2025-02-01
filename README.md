<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FC Invest - Investimentos Inteligentes</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>FC Invest</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#servicos">Serviços</a></li>
                    <li><a href="#sobre">Sobre Nós</a></li>
                    <li><a href="#contato">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="container">
            <h2>Investimentos Inteligentes para o Seu Futuro</h2>
            <p>Conheça nossas soluções de investimento e comece a construir seu patrimônio hoje mesmo.</p>
            <a href="#servicos" class="btn">Saiba Mais</a>
        </div>
    </section>

    <section id="servicos" class="services">
        <div class="container">
            <h2>Nossos Serviços</h2>
            <div class="service-item">
                <h3>Consultoria</h3>
                <p>Oferecemos consultoria personalizada para ajudar você a tomar as melhores decisões de investimento.</p>
            </div>
            <div class="service-item">
                <h3>Gestão de Carteiras</h3>
                <p>Gerenciamos sua carteira de investimentos com estratégias adaptadas ao seu perfil e objetivos.</p>
            </div>
            <div class="service-item">
                <h3>Educação Financeira</h3>
                <p>Cursos e workshops para você aprender mais sobre o mercado financeiro e investimentos.</p>
            </div>
        </div>
    </section>

    <section id="sobre" class="about">
        <div class="container">
            <h2>Sobre Nós</h2>
            <p>A FC Invest é uma empresa especializada em gestão de investimentos, com foco em oferecer soluções personalizadas para nossos clientes. Nossa missão é ajudar você a alcançar seus objetivos financeiros com segurança e eficiência.</p>
        </div>
    </section>

    <section id="contato" class="contact">
        <div class="container">
            <h2>Contato</h2>
            <form id="contact-form">
                <label for="name">Nome:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Mensagem:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Enviar</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 FC Invest. Todos os direitos reservados.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>