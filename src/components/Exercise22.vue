<template>
    <div>
        <div class="header">
            <div class="logo">
                <div class="img">LOGO</div>
            </div>
            <div style="display: flex; align-items: end; flex-direction: column;">
                <div>
                    <input type="text" placeholder="Pesquise aqui">
                </div>
                <div class="menu">
                    <ul>
                        <li>Item</li>
                        <li>Item</li>
                        <li>Item</li>
                        <li>Item</li>
                        <li>Item</li>
                    </ul>
                </div>
            </div>
        </div>

        <hr>

        <div class="body">
            <div class="lateral">
                <div>
                    <span>Categorias</span>
                    <hr>
                    <div class="item-lateral">
                        <div v-for="index in 10" class="categoria">
                            <div class="icon"></div>
                            <span>Categoria {{ index }}</span>
                        </div>
                    </div>
                </div>
                <div>
                    <span>Guias</span>
                    <hr>
                    <div class="item-lateral">
                        <div v-for="index in 5">Guia {{ index }}</div>
                    </div>
                </div>
            </div>
            <div class="main-content">
                <div>
                    <div class="main-img"></div>
                    <div class="secondary-imgs">
                        <div v-for="index in 3" class="secondary-img"></div>
                    </div>
                </div>
                    <div class="secondary-content">
                    <span>Produtos Relacionados</span>
                    <hr>
                    <div class="related-produts">
                        <div v-for="index in 12" class="product">
                            <div class="produtct-img"></div>
                            <span>Nome {{ index }}</span>
                            <span>Valor {{ index }}</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <hr>

        <div class="footer">
            <div>
                <span class="title">Categorias</span>
                <div v-for="index in 5">
                    <span>Categoria {{ index }}</span>
                </div>
            </div>

            <div>
                <span class="title">Menu</span>
                <div v-for="index in 5">
                    <span>Menu {{ index }}</span>
                </div>
            </div>

            <div>
                <span class="title">Guia</span>
                <div v-for="index in 5">
                    <span>Guia {{ index }}</span>
                </div>
            </div>

        </div>
    </div>
    
</template>
  
<script>
export default {
    name: 'Exercise22',
}
</script>

<style scoped>

.header {
    display: grid;
    grid-template-columns: 20% auto;
}

.img {
    width: 125px;
    height: 75px;
    border: 1px solid black;
    display: flex;
    justify-content: center;
    align-items: center;
}
.body{
    display: grid;
    grid-template-columns: 20% auto;
    column-gap: 2rem;
}
.lateral {
    display: flex;
    flex-direction: column;
    gap: 2.5rem;
}
.item-lateral{
    display: flex;
    flex-direction: column;
    gap: 1rem;
}
.categoria {
    display: flex;
    align-items: center;
    gap: 0.5rem;
}
.main-content{
    display: flex;
    flex-direction: column;
    gap: 2rem;
}
.icon {
    width: 40px;
    height: 40px;
    border: 1px solid black;
}

.menu ul li {
    list-style: none;
    padding-right: 1rem;
}

.menu ul li:not(:last-child) {
    border-right: 1px solid black;
}

.menu ul {
    display: flex;
    gap: 1rem;
}
.main-img {
    border: 1px solid black;
    height: 300px;
}

.secondary-img {
    height: 100px;
    border: 1px solid black;
}
.produtct-img {
    height: 150px;
    width: 150px;
    border: 1px solid black;
}
.related-produts {
    display: flex;
    flex-wrap: wrap;
    gap: 5rem;
    justify-content: space-evenly;
}
.product {
    display: flex;
    flex-direction: column;
}
.secondary-imgs {
    display: grid;
    grid-template-columns: auto auto auto;
    gap: 1rem;
    margin-top: 1rem;
}
.title{
    font-weight: 600;
}
.footer {
    padding: 1rem;
    display: flex;
    justify-content: space-around;
}
</style>