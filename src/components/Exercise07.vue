<template>
    <div>
        <span>
            O seguinte código irá renderizar o seguinte conteúdo:
        </span>
        <pre>
            &#x3C;html&#x3E;
            &#x3C;head&#x3E;
            &#x3C;title&#x3E;Exerc&#xED;cio 4 c)&#x3C;/title&#x3E;
            &#x3C;/head&#x3E;
            &#x3C;body&#x3E;
            &#x3C;p&#x3E;&#x3C;a href=&#x22;index.php&#x22;&#x3E;Link 1&#x3C;/a&#x3E;&#x3C;br&#x3E;
            &#x3C;a href=&#x22;http://www.google.com&#x22;&#x3E;Google&#x3C;/a&#x3E;&#x3C;/p&#x3E;
            &#x3C;p&#x3E;&#x3C;a href=&#x22;http://www.yahoo.com&#x22;&#x3E;Yahoo&#x3C;/a&#x3E; &#x3C;/p&#x3E;
            &#x3C;/body&#x3E;
            &#x3C;/html&#x3E;
        </pre> 
        <br> 
        <hr>

        <pre>
            O HTML fornecido cria uma página da web com dois parágrafos, cada um contendo links.

            Resultado de Renderização:

            Primeiro Parágrafo:

            Link 1: Um link de texto chamado "Link 1" que aponta para um arquivo chamado "index.php".
            Google: Um link de texto chamado "Google" que aponta para o site "http://www.google.com".
            Segundo Parágrafo:

            Yahoo: Um link de texto chamado "Yahoo" que aponta para o site "http://www.yahoo.com".
            Portanto, quando a página for renderizada em um navegador, você verá dois parágrafos, e os links serão clicáveis.
            "Link 1" redirecionará para o arquivo "index.php", enquanto "Google" e "Yahoo" redirecionarão para os respectivos sites da web.
            Cada link será apresentado como um hiperlink clicável no navegador.
        </pre>
    </div>
</template>
  
<script>
export default {
    name: 'Exercise07',
}
</script>

<style scoped></style>