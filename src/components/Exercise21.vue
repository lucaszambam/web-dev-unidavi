<template>
    <body>
        <header class="flex column gap-lg">
            <div class="header-top flex center space-between">
                <h1>I ❤ Bolos</h1>
                <div class="searh-links flex center gap-lg">
                    <div class="links flex center gap-md">
                        <a href="#">Perguntas e Respostas</a>
                        <a href="#">Ajuda</a>
                    </div>
                    <div class="search">
                        <button type="submit">🔎</button>
                        <input type="text" placeholder="Pesquise aqui...">
                    </div>
                </div>
            </div>
            <nav>
                <ul class="flex center">
                    <li><a href="#">Sobre</a></li>
                    <li><a href="#">Bolos</a></li>
                    <li><a href="#">Presentes</a></li>
                    <li><a href="#">Comprar</a></li>
                    <li><a href="#">Guia</a></li>
                    <li><a href="#">Blog</a></li>
                </ul>
            </nav>
        </header>
        <main class="flex space-between">
            <div class="lateral flex column space-between gap-lg">
                <div class="acesso flex column">
                    <h2>Acesso</h2>
                    <form class="flex column center gap-sm" id="login-form" method="post">
                        <div>
                            <label for="email">Email:</label>
                            <input type="email" id="email" name="email" required>
                        </div>
                        <div>
                            <label for="password">Senha:</label>
                            <input type="password" id="password" name="password" required>
                        </div>

                        <a href="#">Perdeu o seu password?</a>

                        <button type="submit">Entrar</button>
                    </form>
                </div>
                <div class="bolos">
                    <h2>Bolos</h2>
                    <ul class="flex column gap-sm">
                        <li><a href="#">Simples</a></li>
                        <li><a href="#">Chocolate</a></li>
                        <li><a href="#">Creme</a></li>
                        <li><a href="#">Frutas</a></li>
                        <li><a href="#">Baixa caloria</a></li>
                    </ul>
                </div>
                <div class="video">
                    <h2>Vídeo</h2>
                    <video controls>
                        <source
                            src="https://www.shutterstock.com/shutterstock/videos/1063145557/preview/stock-footage-eating-brownie-with-fork-taking-bite-of-chocolate-cake-with-chocolate-icing-and-raspberries.webm"
                            type="video/webm">
                        Seu navegador não suporta o elemento de vídeo.
                    </video>
                </div>
            </div>
            <div class="principal flex column">
                <div class="banner">
                    <img src="banner-bolo.png" alt="Bolos">
                </div>

                <div class="vitrine">
                    <div class="menu-vitrine flex center">
                        <a class="ativo" href="#">Novos!</a>
                        <a href="#">Ranking</a>
                        <a href="#">Recomendados</a>
                        <a href="#">Baixa caloria</a>
                    </div>

                    <div class="produtos flex space-between">
                        <div class="produto flex column gap-sm">
                            <img src="https://d1uz88p17r663j.cloudfront.net/original/8fee36bf950557ff9f896b9104f36907_bolo-vulcao-brigadeiro-receitas-nestle.jpg"
                                alt="Bolo">
                            <h3>Bolo pequeno</h3>
                            <span>R$ 49,90</span>
                            <span>1000kcal</span>
                        </div>

                        <div class="produto flex column gap-sm">
                            <img src="https://d1uz88p17r663j.cloudfront.net/original/8fee36bf950557ff9f896b9104f36907_bolo-vulcao-brigadeiro-receitas-nestle.jpg"
                                alt="Bolo">
                            <h3>Bolo pequeno</h3>
                            <span>R$ 49,90</span>
                            <span>1000kcal</span>
                        </div>

                        <div class="produto flex column gap-sm">
                            <img src="https://d1uz88p17r663j.cloudfront.net/original/8fee36bf950557ff9f896b9104f36907_bolo-vulcao-brigadeiro-receitas-nestle.jpg"
                                alt="Bolo">
                            <h3>Bolo pequeno</h3>
                            <span>R$ 49,90</span>
                            <span>1000kcal</span>
                        </div>

                        <div class="produto flex column gap-sm">
                            <img src="https://d1uz88p17r663j.cloudfront.net/original/8fee36bf950557ff9f896b9104f36907_bolo-vulcao-brigadeiro-receitas-nestle.jpg"
                                alt="Bolo">
                            <h3>Bolo pequeno</h3>
                            <span>R$ 49,90</span>
                            <span>1000kcal</span>
                        </div>

                        <div class="produto flex column gap-sm">
                            <img src="https://d1uz88p17r663j.cloudfront.net/original/8fee36bf950557ff9f896b9104f36907_bolo-vulcao-brigadeiro-receitas-nestle.jpg"
                                alt="Bolo">
                            <h3>Bolo pequeno</h3>
                            <span>R$ 49,90</span>
                            <span>1000kcal</span>
                        </div>
                    </div>
                </div>

                <div class="information">
                    <div class="title flex center space-between">
                        <h2>Informações</h2>
                        <a href="#">Mais...</a>
                    </div>
                    <div class="content flex column gap-sm">
                        <a href="#">Janeiro 1, 2011 Informação</a>
                        <a href="#">Janeiro 1, 2011 Informação</a>
                        <a href="#">Janeiro 1, 2011 Informação</a>
                    </div>
                </div>
            </div>
        </main>
        <footer>
            <div class="flex center space-between">
                <div class="flex center gap-lg">
                    <strong>I ❤ Bolos</strong>
                    <div>
                        <a href="#">Sobre</a>
                        <a href="#">Presente</a>
                        <a href="#">Comprar</a>
                        <a href="#">Guia</a>
                        <a href="#">Blog</a>
                    </div>
                </div>
                <div class="social flex center gap-md">
                    <a href="#"><img src="https://cdn.icon-icons.com/icons2/2972/PNG/512/facebook_logo_icon_186880.png"
                            alt="Facebook"></a>
                    <a href="#"><img src="https://cdn.pixabay.com/photo/2021/06/15/12/14/instagram-6338392_1280.png"
                            alt="Instagram"></a>
                    <a href="#"><img
                            src="https://png.pngtree.com/png-clipart/20221019/original/pngtree-twitter-social-media-round-icon-png-image_8704823.png"
                            alt="Twitter"></a>
                    <a href="#"><img src="https://cdn.icon-icons.com/icons2/2992/PNG/512/tiktok_logo_icon_187324.png"
                            alt="Tiktok"></a>
                </div>
            </div>
            <div class="copyright flex center justify-center">
                <p>&copy; 2023 Seu Site. Todos os direitos reservados.</p>
            </div>
        </footer>
    </body>
</template>
  
<script>
export default {
    name: 'Exercise21',
}
</script>

<style scoped>
 * {
        margin: 0;
        padding: 0;
        text-decoration: none;
        list-style: none;
    }

    .flex {
        display: flex;
    }

    .column {
        flex-direction: column;
    }

    .center {
        align-items: center;
    }

    .justify-center {
        justify-content: center;
    }

    .space-between {
        justify-content: space-between;
    }

    .gap-sm {
        gap: 8px;
    }

    .gap-md {
        gap: 16px;
    }

    .gap-lg {
        gap: 32px;
    }

    body {
        padding: 20px 56px;
    }

    h1 {
        margin: 0;
    }

    .search {
        border: 1px solid #ccc;
        border-radius: 16px;
        padding: 4px 8px;
    }

    .search button {
        border: none;
        background: transparent;
        cursor: pointer;
    }

    .search input {
        border: none;
        outline: none;
    }

    nav ul li {
        list-style: none;
        text-align: center;
        background: #ccc;
        border: 2px solid #b1b1b1;
        width: calc(100% / 6);
        padding: 4px 0;
        cursor: pointer;
    }

    nav ul li:hover {
        background: #b1b1b1;
    }

    nav ul li a {
        color: #000;
        text-decoration: none;
    }

    .lateral {
        width: 20%;
        height: 100%;
        margin: 32px 0;
    }

    .lateral > div {
        border: 2px solid #575757;
        border-radius: 8px 8px 0 0;
        overflow: hidden;
    }

    .lateral h2 {
        background: #575757;
        color: #fff;
        font-size: 18px;
        margin: 0;
        width: 100%;
        padding: 8px 16px;
    }

    .lateral ul {
        margin: 16px 24px;
    }

    .lateral video {
        width: calc(100% - 32px);
        height: auto;
        padding: 0 16px;
        margin: 32px 0;
    }

    .acesso form {
        margin: 24px;
    }

    .acesso a {
        text-decoration: underline;
    } 

    .acesso button {
        padding: 8px 24px;
        background: #ccc;
        border-radius: 4px;
        cursor: pointer;
    }

    .acesso button:hover {
        background: #b1b1b1;
    }

    .principal {
        width: 70%;
        margin: 32px 0;
    }

    .principal .banner {
        border: 3px solid #b5b5b5;
    }

    .principal .banner img {
        width: 100%;
        height: auto;
    }

    .vitrine {
        width: 100%;
        margin: 24px 0;
    }

    .vitrine .menu-vitrine a {
        color: #000;
        width: calc(100% / 4);
        text-align: center;
        background-color: #b5b5b5;
        border: 2px solid #929292;
        border-radius: 8px 8px 0 0;
        padding: 8px 16px;
    }

    .vitrine .menu-vitrine a.ativo,
    .vitrine .menu-vitrine a:hover {
        background: #dddddd;
    }

    .vitrine .produtos {
        padding: 32px 16px;
        border: 2px solid #929292;
        border-top: none;
    }

    .vitrine .produto {
        width: calc(100% / 5.5);
    }

    .vitrine .produto h3 {
        font-size: 16px;
    }

    .vitrine .produto img {
        width: auto;
        height: 150px;
    }

    .information {
        width: 100%;
    }

    .information .title {
        background: #575757;
        color: #fff;
        padding: 8px 16px;
        border-radius: 8px 8px 0 0;
    }
    
    .information .title h2 {
        font-size: 18px;
    }

    .information .title a {
        color: #fff;
    }

    .information .content {
        padding: 32px 16px;
        border: 2px solid #929292;
        border-top: none;
    }

    footer {
        margin-top: 32px;
        padding: 32px 0;
        border-top: 2px dashed #929292;
    }

    footer strong {
        font-size: 32px;
    }

    .social img {
        width: 50px;
        height: 50px;
    }

    .copyright {
        margin-top: 32px;
    }
    </style>