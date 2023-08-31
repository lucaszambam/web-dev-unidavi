<template>
    <div>

        <body>
            <header>
                <h1>Logo</h1>

                <nav>
                    <h3>Menu</h3>
                    <h3>Menu</h3>
                    <h3>Menu</h3>
                    <h3>Menu</h3>
                    <h3>Menu</h3>
                </nav>

            </header>

            <section>
                <div class="photo-container">
                    <div class="photo">
                        <span>Foto</span>
                    </div>
                    <div>
                        <p>à 37 minutos</p>
                        <h4>Título</h4>
                    </div>
                </div>
                <div class="photo-container">
                    <div class="photo">
                        <span>Foto</span>
                    </div>
                    <div>
                        <p>à 37 minutos</p>
                        <h4>Título</h4>
                    </div>
                </div>
                <div class="photo-container">
                    <div class="photo">
                        <span>Foto</span>
                    </div>
                    <div>
                        <p>à 37 minutos</p>
                        <h4>Título</h4>
                    </div>
                </div>
                <div class="photo-container">
                    <div class="photo">
                        <span>Foto</span>
                    </div>
                    <div>
                        <p>à 37 minutos</p>
                        <h4>Título</h4>
                    </div>
                </div>
                <div class="photo-container">
                    <div class="photo">
                        <span>Foto</span>
                    </div>
                    <div>
                        <p>à 37 minutos</p>
                        <h4>Título</h4>
                    </div>
                </div>
                <div class="photo-container">
                    <div class="photo">
                        <span>Foto</span>
                    </div>
                    <div>
                        <p>à 37 minutos</p>
                        <h4>Título</h4>
                    </div>
                </div>
                <div class="photo-container">
                    <div class="photo">
                        <span>Foto</span>
                    </div>
                    <div>
                        <p>à 37 minutos</p>
                        <h4>Título</h4>
                    </div>
                </div>
                <div class="photo-container">
                    <div class="photo">
                        <span>Foto</span>
                    </div>
                    <div>
                        <p>à 37 minutos</p>
                        <h4>Título</h4>
                    </div>
                </div>
                <div class="photo-container">
                    <div class="photo">
                        <span>Foto</span>
                    </div>
                    <div>
                        <p>à 37 minutos</p>
                        <h4>Título</h4>
                    </div>
                </div>
                <div class="photo-container">
                    <div class="photo">
                        <span>Foto</span>
                    </div>
                    <div>
                        <p>à 37 minutos</p>
                        <h4>Título</h4>
                    </div>
                </div>
                <div class="photo-container">
                    <div class="photo">
                        <span>Foto</span>
                    </div>
                    <div>
                        <p>à 37 minutos</p>
                        <h4>Título</h4>
                    </div>
                </div>
                <div class="photo-container">
                    <div class="photo">
                        <span>Foto</span>
                    </div>
                    <div>
                        <p>à 37 minutos</p>
                        <h4>Título</h4>
                    </div>
                </div>
            </section>

            <div class="bottom-button">
                <h3>Mais</h3>
            </div>

        </body>
    </div>
</template>
  
<script>
export default {
    name: 'Exercise20',
}
</script>

<style scoped>
body {
    display: flex;
    flex-direction: column;
    align-items: center;
}

section {
    width: 80vw;
    height: 100vh;
    display: flex;
    margin-top: 2%;
    gap: 20px;
    justify-content: center;
    flex-wrap: wrap;
}

header {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

header h1 {
    padding-top: 16px;
    padding-bottom: 16px;
    font-size: 42pt;
}

nav {
    display: flex;
    gap: 125px;
    justify-content: center;
    padding-top: 8px;
    padding-bottom: 8px;
    border-top: 1px solid black;
    border-bottom: 1px solid black;
    width: 100vw;
}

.photo-container {
    display: flex;
    flex-direction: column;
}

.photo {
    height: 225px;
    width: 225px;
    background: rgb(180, 180, 180);
    display: flex;
    align-items: center;
    justify-content: center;
}

.bottom-button {
    width: 450px;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: rgb(180, 180, 180);
    margin-top: 5%;
}

.bottom-button h3 {

    font-weight: lighter;
}
</style>