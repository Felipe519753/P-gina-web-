

```
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grupo de Desenvolvedores</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <section class="livros">
        <h2 class="livros__titulo">Livros Recomendados</h2>
        <div class="swiper">
            <div class="swiper-wrapper">
                <div class="swiper-slide"><img src="img/Livro1.svg" alt="Livro 1"></div>
                <div class="swiper-slide"><img src="img/Livro2.svg" alt="Livro 2"></div>
                <div class="swiper-slide"><img src="img/Livro3.svg" alt="Livro 3"></div>
            </div>
            <div class="swiper-button-prev"></div>
            <div class="swiper-button-next"></div>
        </div>
    </section>
    <div class="card">
        <div class="card__descrição">
            <div class="descrição">
                <img src="img/Estrelinhas.svg" alt="Avaliação 5 estrelas">
                <h3 class="descrição__titulo">Autor do Mês</h3>
                <h2 class="descrição__titulo-livro">João Silva</h2>
                <p class="descrição__texto">Desenvolvedor web e escritor, João é especialista em Back-End.</p>
            </div>
            <img src="img/Escritor.svg" class="descrição__imagem">
        </div>
        <div class="card__botões">
            <ul class="botões">
                <li class="botões__item"><img src="img/Favoritos.svg" alt="Favoritar livro"></li>
                <li class="botões__item"><img src="img/Compras.svg" alt="Adicionar no carrinho de compras"></li>
            </ul>
            <a href="#" class="botões__ancora">Saiba mais</a>
        </div>
    </div>
    <section class="tópicos">
        <h2 class="tópicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
        <ul class="tópicos__lista">
            <li class="tópicos__item"><a href="#" class="tópicos__link">Desenvolvimento Web</a></li>
            <li class="tópicos__item"><a href="#" class="tópicos__link">Inteligência Artificial</a></li>
            <li class="tópicos__item"><a href="#" class="tópicos__link">Cybersegurança</a></li>
            <li class="tópicos__item"><a href="#" class="tópicos__link">Data Science</a></li>
        </ul>
    </section>
    <section class="contato">
        <div class="contato__descrição">
            <h2 class="contato__titulo">Fique por dentro das novidades!</h2>
            <p class="contato__texto">Atualizações de e-books, novos livros, promoções e outros.</p>
        </div>
        <input type="email" placeholder="Cadastre seu e-mail" class="contato__email">
    </section>
    <hr />
    <footer class="rodapé">
        <h2 class="rodapé__titulo">Grupo de Desenvolvedores</h2>
        <ul class="lista-rodapé">
            <li class="lista-rodapé__titulo">Educação</li>
            <li class="lista-rodapé__item"><img src="img/Logo1.svg" alt="Logo 1"><a href="#" class="lista-rodapé__link">Curso 1</a></li>
            <li class="lista-rodapé__item"><img src="img/Logo2.svg" alt="Logo 2"><a href="#" class="lista-rodapé__link">Curso 2</a></li>
        </ul>
    </footer>
    <script src="(link unavailable)"></script>
    <script>
        const swiper = new Swiper(".swiper", {
            spaceBetween: 10,
            slidesPerView: 3,
            pagination: {
```Aqui está o código completo:

```
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grupo de Desenvolvedores</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <section class="livros">
        <h2 class="livros__titulo">Livros Recomendados</h2>
        <div class="swiper">
            <div class="swiper-wrapper">
                <div class="swiper-slide"><img src="img/Livro1.svg" alt="Livro 1"></div>
                <div class="swiper-slide"><img src="img/Livro2.svg" alt="Livro 2"></div>
                <div class="swiper-slide"><img src="img/Livro3.svg" alt="Livro 3"></div>
            </div>
            <div class="swiper-button-prev"></div>
            <div class="swiper-button-next"></div>
        </div>
    </section>
    <div class="card">
        <div class="card__descrição">
            <div class="descrição">
                <img src="img/Estrelinhas.svg" alt="Avaliação 5 estrelas">
                <h3 class="descrição__titulo">Autor do Mês</h3>
                <h2 class="descrição__titulo-livro">João Silva</h2>
                <p class="descrição__texto">Desenvolvedor web e escritor, João é especialista em Back-End.</p>
            </div>
            <img src="img/Escritor.svg" class="descrição__imagem">
        </div>
        <div class="card__botões">
            <ul class="botões">
                <li class="botões__item"><img src="img/Favoritos.svg" alt="Favoritar livro"></li>
                <li class="botões__item"><img src="img/Compras.svg" alt="Adicionar no carrinho de compras"></li>
            </ul>
            <a href="#" class="botões__ancora">Saiba mais</a>
        </div>
    </div>
    <section class="tópicos">
        <h2 class="tópicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
        <ul class="tópicos__lista">
            <li class="tópicos__item"><a href="#" class="tópicos__link">Desenvolvimento Web</a></li>
            <li class="tópicos__item"><a href="#" class="tópicos__link">Inteligência Artificial</a></li>
            <li class="tópicos__item"><a href="#" class="tópicos__link">Cybersegurança</a></li>
            <li class="tópicos__item"><a href="#" class="tópicos__link">Data Science</a></li>
        </ul>
    </section>
    <section class="contato">
        <div class="contato__descrição">
            <h2 class="contato__titulo">Fique por dentro das novidades!</h2>
            <p class="contato__texto">Atualizações de e-books, novos livros, promoções e outros.</p>
        </div>
        <input type="email" placeholder="Cadastre seu e-mail" class="contato__email">
    </section>
    <hr />
    <footer class="rodapé">
        <h2 class="rodapé__titulo">Grupo de Desenvolvedores</h2>
        <ul class="lista-rodapé">
            <li class="lista-rodapé__titulo">Educação</li>
            <li class="lista-rodapé__item"><img src="img/Logo1.svg" alt="Logo 1"><a href="#" class="lista-rodapé__link">Curso 1</a></li>
            <li class="lista-rodapé__item"><img src="img/Logo2.svg" alt="Logo 2"><a href="#" class="lista-rodapé__link">Curso 2</a></li>
        </ul>
    </footer>
    <script src="(link unavailable)"></script>
    <script>
        const swiper = new Swiper(".swiper", {
            spaceBetween: 10,
            slidesPerView: 3,
            pagination: {
```
