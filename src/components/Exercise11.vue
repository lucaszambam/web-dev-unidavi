<template>
    <div>
        <span>
            O seguinte código irá renderizar a seguinte tabela:
        </span>
        <pre>
            &#x3C;html&#x3E;
            &#x3C;head&#x3E;
            &#x3C;title&#x3E;Exerc&#xED;cio 11&#x3C;/title&#x3E;
            &#x3C;/head&#x3E;
            &#x3C;body&#x3E;
            &#x3C;form name=&#x22;form1&#x22; method=&#x22;post&#x22; action=&#x22;&#x22;&#x3E;
            &#x3C;table border=&#x22;1&#x22; align=&#x22;center&#x22;&#x3E;
            &#x3C;tr&#x3E;
            &#x3C;td align=&#x22;right&#x22; valign=&#x22;top&#x22;&#x3E;Usuario:&#x3C;/td&#x3E;&#x3C;td&#x3E;&#x3C;input name=&#x22;usuario&#x22; type=&#x22;text&#x22;
            id=&#x22;usuario&#x22;&#x3E;&#x3C;/td&#x3E;
            &#x3C;/tr&#x3E;&#x3C;tr&#x3E;
            &#x3C;td align=&#x22;right&#x22; valign=&#x22;top&#x22;&#x3E;Senha: &#x3C;/td&#x3E;&#x3C;td&#x3E;&#x3C;input name=&#x22;senha&#x22; type=&#x22;password&#x22;
            id=&#x22;senha&#x22;&#x3E;&#x3C;/td&#x3E;
            &#x3C;/tr&#x3E;&#x3C;tr&#x3E;
            &#x3C;td align=&#x22;right&#x22; valign=&#x22;top&#x22;&#x3E;Endere&#x26;ccedil;o: &#x3C;/td&#x3E;&#x3C;td&#x3E;&#x3C;textarea name=&#x22;end&#x22; rows=&#x22;5&#x22;
            id=&#x22;end&#x22;&#x3E;&#x3C;/textarea&#x3E;&#x3C;/td&#x3E;
            &#x3C;/tr&#x3E;&#x3C;tr&#x3E;
            &#x3C;td align=&#x22;right&#x22; valign=&#x22;top&#x22;&#x3E;Idade: &#x3C;/td&#x3E;&#x3C;td&#x3E;&#x3C;select name=&#x22;idade&#x22; size=&#x22;3&#x22; id=&#x22;idade&#x22;&#x3E;
            &#x3C;option value=&#x22;1&#x22;&#x3E;menos de 25&#x3C;/option&#x3E;
            &#x3C;option value=&#x22;2&#x22;&#x3E;entre 25 e 50&#x3C;/option&#x3E;
            &#x3C;option value=&#x22;3&#x22;&#x3E;mais de 50&#x3C;/option&#x3E;
            &#x3C;/select&#x3E;
            &#x3C;/td&#x3E;
            &#x3C;/tr&#x3E;&#x3C;tr&#x3E;
            &#x3C;td align=&#x22;right&#x22; valign=&#x22;top&#x22;&#x3E;Sexo: &#x3C;/td&#x3E;&#x3C;td&#x3E;&#x3C;p&#x3E;
            &#x3C;label&#x3E;
            &#x3C;input type=&#x22;radio&#x22; name=&#x22;sexo&#x22; value=&#x22;m&#x22;&#x3E;
            masculino&#x3C;/label&#x3E;
            &#x3C;br&#x3E;
            &#x3C;label&#x3E;
            &#x3C;input type=&#x22;radio&#x22; name=&#x22;sexo&#x22; value=&#x22;f&#x22;&#x3E;
            feminino&#x3C;/label&#x3E;
            &#x3C;br&#x3E;
            &#x3C;/p&#x3E;&#x3C;/td&#x3E;
            &#x3C;/tr&#x3E;&#x3C;tr&#x3E;
            &#x3C;td align=&#x22;right&#x22; valign=&#x22;top&#x22;&#x3E;Eu concordo:&#x3C;/td&#x3E;&#x3C;td&#x3E;&#x3C;input name=&#x22;concordo&#x22;
            type=&#x22;checkbox&#x22; id=&#x22;concordo&#x22; value=&#x22;1&#x22;&#x3E;&#x3C;/td&#x3E;
            &#x3C;/tr&#x3E;&#x3C;tr&#x3E;
            &#x3C;td colspan=&#x22;2&#x22; align=&#x22;center&#x22;&#x3E;&#x3C;input type=&#x22;submit&#x22; name=&#x22;Submit&#x22; value=&#x22;Submit&#x22;&#x3E;&#x3C;/td&#x3E;
            &#x3C;/tr&#x3E;
            &#x3C;/table&#x3E;
            &#x3C;/form&#x3E;
            &#x3C;/body&#x3E;
            &#x3C;/html&#x3E;
        </pre> 
        <br> 
        <hr>

        <pre>
            ----------------------------------
            |     Usuario: |                 |
            ----------------------------------
            |       Senha: |                 |
            ----------------------------------
            |    Endereço: |                 |
            |              |                 |
            |              |                 |
            ----------------------------------
            |       Idade: | menos de 25     |
            |	           | entre 25 e 50   |
            |              | mais de 50      |
            ----------------------------------
            |        Sexo: | º masculino     |
            |              | º feminino      |
            ----------------------------------
            | Eu Concordo: | [ ]             |
            ----------------------------------
            |               Submit           |
            ----------------------------------

        </pre>
    </div>
</template>
  
<script>
export default {
    name: 'Exercise11',
}
</script>

<style scoped></style>