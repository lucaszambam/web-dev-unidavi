<template>
    <div>
        <header>
        <div class="banner">
            <img src="Imagens/google-logoblog.png" alt="logo">
        </div>
    </header>
    <nav>
        <a href='#'>Menu</a>
        <a href='#'>Menu</a>
        <a href='#'>Menu</a>
        <a href='#'>Menu</a>
        <a href='#'>Menu</a>
    </nav>
    <main>
        <div class="advertisement">
            <h2 class="title">Publicidade</h2>
            <p>Lorem ipsum dolor sit amet consecteturiutem et.</p>
        </div>
        <h2 class="title">Titulo</h2>
        <div class="lorem-container">
            <p class="lorem">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Minus ullam iusto ipsa nisi pariatur obcaecati incidunt molestias, facilis fugiat sunt necessitatibus illum deserunt consequuntur dolor praesentium, tempore, at excepturi adipisci?</p>
            <p class="lorem">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Deleniti cumque ratione architecto modi iusto soluta natus. Accusantium minima similique laborum ducimus facilis corporis doloremque saepe aliquam labore, odio nam rerum.</p>
        </div>
        <div class="content-container">
            <div class="content">
                <h2>Conteúdo</h2>
                <p>Este é o conteúdo do primeiro bloco.</p>
            </div>
            <div class="content">
                <h2>Conteúdo</h2>
                <p>Este é o conteúdo do segundo bloco.</p>
            </div>
            <div class="content">
                <h2>Conteúdo</h2>
                <p>Este é o conteúdo do terceiro bloco.</p>
            </div>
        </div>
        <div class="contact-button">
            <button>Contato</button>
        </div>
    </main>
    
    <footer>
        <div>
            <img src="Imagens/google-logoblog.png" alt="logo">
        </div>
        <div>
            <div>
                <img src="" alt="">
            </div>
            <nav>
                <a href='#'>Menu</a>
                <a href='#'>Menu</a>
                <a href='#'>Menu</a>
                <a href='#'>Menu</a>
                <a href='#'>Menu</a>
            </nav>
            <div class="social-icons">
                <div class="social-icons-1">
                    <img src="Imagens/Facebook_f_logo_(2019).svg.png" alt="Facebook">
                </div>
                <div class="social-icons-2">
                    <img src="Imagens/Twitter_bird_logo.svg.png" alt="Twitter">
                </div>
            </div>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
            </p>
        </div>
    </footer>
    </div>
    
</template>
  
<script>
export default {
    name: 'Exercise19',
}
</script>

<style scoped>
body {
    background-color: lightgray;
    font-family: Arial, sans-serif;
}

header {
    display: flex;
    flex-direction: column; 
    align-items: center;
    background-color: lightgray;
    padding-bottom: 20px;
    padding-top: -10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
.banner {
    text-align: center;
    color: #fff;
    padding-top: 50px;
    margin-bottom: -10px; 
    margin-top: -20px;
}

.banner img {
    max-width: 300px; 
    height: auto; 
}
nav {
    text-align: center;
    background-color: #333;
    padding: 10px 0;
}

nav a {
    margin-right: 15px;
    text-decoration: none;
    color: #ffffff;
    position: relative; 
}

nav a:not(:last-child)::after {
    content: "|"; 
    position: absolute;
    right: -10px; 
    color: #ffffff;
}
main {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

h1 {
    font-size: 24px;
    margin-bottom: 10px;
}

h2 {
    font-size: 20px;
    margin-top: 20px;
    margin-bottom: 10px;
}

p {
    margin-bottom: 15px;
}

img {
    max-width: 100%;
    height: auto;
    padding-bottom: -10px;
}

footer {
    background-color: #8b8080;
    color: #fff;
    padding: 20px;
    text-align: center;
}

footer a {
    color: #ffffff;
    text-decoration: none;
    margin-right: 10px;
}

.social-icons {
    display: flex;
    justify-content: center;
    align-items: center; 
    margin-top: 20px;
    margin-bottom: 10px;
}

.social-icons .social-icons-1 img {
    width: 30px; 
    height: 30px; 
    margin: 0 5px; 
}

.social-icons .social-icons-2 img {
    width: 37px; 
    height: 37px; 
    margin: 0 5px; 
}
.advertisement {
    text-align: center;
    padding: 20px;
}

.advertisement p {
    font-size: 15px; 
}

.advertisement h2 {
    font-size: 24px; 
}

.title {
    text-align: center;
    margin-bottom: 20px;
}

.lorem-container {
    display: flex; 
    align-items: center; 
    justify-content: center; 
    margin-top: 20px;
}

.lorem {
    margin: 0 10px; 
}

.content-container {
    display: flex; 
    justify-content: space-between; 
    margin-top: 20px;
}
.content {
    width: calc(33.33% - 10px); 
    padding: 10px;
    background-color: #fff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.contact-button {
    display: flex;
    justify-content: center;
    margin-top: 20px;
}

.contact-button button {
    padding: 10px 20px;
    background-color: #333;
    color: #fff;
    border: none;
    cursor: pointer;
}

footer img {
    max-width: 150px;
    height: auto;
}
</style>