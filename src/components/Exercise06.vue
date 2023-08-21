<template>
    <div>
        <span>
            O seguinte código irá renderizar a seguinte tabela:
        </span>
        <pre>
            &#x3C;html&#x3E;
            &#x3C;head&#x3E;
            &#x3C;title&#x3E;Exerc&#xED;cio 4 b)&#x3C;/title&#x3E;
            &#x3C;/head&#x3E;
            &#x3C;body&#x3E;
            &#x3C;table border=&#x22;1&#x22;&#x3E;
            &#x3C;tr&#x3E;
            &#x3C;td colspan=&#x22;3&#x22;&#x3E;&#x3C;h1&#x3E;123&#x3C;/h1&#x3E;&#x3C;/td&#x3E;
            &#x3C;/tr&#x3E;
            &#x3C;tr&#x3E;
            &#x3C;td rowspan=&#x22;2&#x22;&#x3E;47&#x3C;/td&#x3E;&#x3C;td&#x3E;5&#x3C;/td&#x3E;&#x3C;td&#x3E;6&#x3C;/td&#x3E;
            &#x3C;/tr&#x3E;
            &#x3C;tr&#x3E;
            &#x3C;td colspan=&#x22;2&#x22;&#x3E;89&#x3C;/td&#x3E;
            &#x3C;/tr&#x3E;
            &#x3C;/table&#x3E;
            &#x3C;/body&#x3E;
            &#x3C;/html&#x3E;
        </pre> 
        <br> 
        <hr>

        <pre>
            |     123    |
            | 47 | 5 | 6 |
            |    |   89  |
        </pre>
    </div>
</template>
  
<script>
export default {
    name: 'Exercise06',
}
</script>

<style scoped></style>