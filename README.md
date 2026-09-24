
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog de Tecnologia e Desenvolvimento</title>
</head>
<body>

    <header>
        <h1>Blog Dev & Tech</h1>
        <nav>
            <ul>
                <li><a href="#artigos">Artigos</a></li>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#inscricao">Inscrição</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="artigos">
            <article>
                <h2>A Importância da HTML Semântica</h2>
                <p>A estruturação semântica do código garante melhor acessibilidade para leitores de tela e otimização para motores de busca (SEO).</p>
                <img src="https://via.placeholder.com/600x300" alt="Código HTML sendo estruturado no editor">
            </article>

            <article>
                <h2>Validação de Formulários Nativa no HTML5</h2>
                <p>Utilizar atributos nativos como pattern, min, max e required garante que os dados cheguem corretos ao servidor sem necessidade inicial de JavaScript.</p>
                <img src="https://via.placeholder.com/600x300" alt="Formulário web em tela com mensagens de validação">
            </article>
        </section>
    </main>

    <aside id="inscricao">
        <h2>Receba as Novidades</h2>
        
        <form action="#" method="get">
            <fieldset>
                <legend>Formulário de Inscrição na Newsletter</legend>

                <p>
                    <label for="nome">Nome Completo:</label><br>
                    <input 
                        type="text" 
                        id="nome" 
                        name="nome" 
                        required 
                        pattern=".{3,}" 
                        title="O nome deve conter no mínimo 3 caracteres."
                    >
                </p>

                <p>
                    <label for="email">E-mail:</label><br>
                    <input 
                        type="email" 
                        id="email" 
                        name="email" 
                        required
                    >
                </p>

                <p>
                    <label for="idade">Idade:</label><br>
                    <input 
                        type="number" 
                        id="idade" 
                        name="idade" 
                        min="18" 
                        max="120" 
                        required
                    >
                </p>

                <p>
                    <label for="assunto">Assunto do seu interesse:</label><br>
                    <select id="assunto" name="assunto" required>
                        <option value="">-- Selecione uma opção --</option>
                        <option value="front-end">Desenvolvimento Front-end</option>
                        <option value="back-end">Desenvolvimento Back-end</option>
                        <option value="carreira">Carreira e Dicas</option>
                    </select>
                </p>

                <p>
                    <input type="checkbox" id="termos" name="termos" required>
                    <label for="termos">Aceito os termos e condições de uso</label>
                </p>

                <p>
                    <button type="submit">Inscrever-se</button>
                </p>
            </fieldset>
        </form>
    </aside>

    <footer>
        <p>&copy; 2026 Blog Dev & Tech - Todos os direitos reservados.</p>
    </footer>

</body>
</html>

