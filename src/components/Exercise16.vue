<template>
    <div>
        <span>
            HTML Formatado:
        </span>
        <pre>
            &#x3C;!DOCTYPE html&#x3E;
            &#x3C;html&#x3E;
            &#x3C;head&#x3E;
                &#x3C;title&#x3E;Exerc&#xED;cio 10&#x3C;/title&#x3E;
            &#x3C;/head&#x3E;
            &#x3C;body bgcolor=&#x22;#AAAAFF&#x22; text=&#x22;darkblue&#x22; link=&#x22;blue&#x22; vlink=&#x22;lightblue&#x22; alink=&#x22;white&#x22;&#x3E;
                &#x3C;h1 align=&#x22;center&#x22;&#x3E;Utilizando &#xC2;ncoras&#x3C;/h1&#x3E;
                &#x3C;h3 align=&#x22;center&#x22;&#x3E;&#x3C;font color=&#x22;white&#x22;&#x3E;Nome, N&#xFA;mero e Turma dos Integrantes&#x3C;/font&#x3E;&#x3C;/h3&#x3E;
                &#x3C;a name=&#x22;topo&#x22;&#x3E;&#x3C;/a&#x3E;
                &#x3C;a href=&#x22;#LO&#x22;&#x3E;Lista Ordenada&#x3C;/a&#x3E;&#x3C;br&#x3E;
                &#x3C;a href=&#x22;#LNO&#x22;&#x3E;Lista N&#xE3;o Ordenada&#x3C;/a&#x3E;&#x3C;br&#x3E;
                &#x3C;a href=&#x22;#LAO&#x22;&#x3E;Lista Aninhada Ordenada&#x3C;/a&#x3E;&#x3C;br&#x3E;
                &#x3C;a href=&#x22;#LANO&#x22;&#x3E;Lista Aninhada N&#xE3;o Ordenada&#x3C;/a&#x3E;&#x3C;p&#x3E;
                &#x3C;hr&#x3E;
                &#x3C;a name=&#x22;LO&#x22;&#x3E;&#x3C;/a&#x3E;
                &#x3C;h2 align=&#x22;center&#x22;&#x3E;Lista Ordenada&#x3C;/h2&#x3E;
                &#x3C;hr&#x3E;
                &#x3C;ol&#x3E;
                    &#x3C;li&#x3E;Curso T&#xE9;cnico em Inform&#xE1;tica&#x3C;/li&#x3E;
                    &#x3C;li&#x3E;Curso T&#xE9;cnico em Turismo&#x3C;/li&#x3E;
                &#x3C;/ol&#x3E;
                &#x3C;a href=&#x22;#topo&#x22;&#x3E;Volta ao In&#xED;cio&#x3C;/a&#x3E;&#x3C;br&#x3E;
                &#x3C;!-- 2a &#xE2;ncora --&#x3E;
                &#x3C;hr&#x3E;
                &#x3C;a name=&#x22;LNO&#x22;&#x3E;&#x3C;/a&#x3E;
                &#x3C;h2 align=&#x22;center&#x22;&#x3E;Lista N&#xE3;o Ordenada&#x3C;/h2&#x3E;
                &#x3C;hr&#x3E;
                &#x3C;ul&#x3E;
                    &#x3C;li&#x3E;Curso T&#xE9;cnico em Eletr&#xF4;nica&#x3C;/li&#x3E;
                    &#x3C;li&#x3E;Curso T&#xE9;cnico em Qu&#xED;mica&#x3C;/li&#x3E;
                &#x3C;/ul&#x3E;
                &#x3C;a href=&#x22;#topo&#x22;&#x3E;Volta ao In&#xED;cio&#x3C;/a&#x3E;&#x3C;br&#x3E;
                &#x3C;!-- 3a &#xE2;ncora --&#x3E;
                &#x3C;hr&#x3E;
                &#x3C;a name=&#x22;LAO&#x22;&#x3E;&#x3C;/a&#x3E;
                &#x3C;h2 align=&#x22;center&#x22;&#x3E;Lista Aninhada Ordenada&#x3C;/h2&#x3E;
                &#x3C;hr&#x3E;
                &#x3C;ol&#x3E;
                    &#x3C;li&#x3E;Curso T&#xE9;cnico em Inform&#xE1;tica
                        &#x3C;ol&#x3E;
                            &#x3C;li&#x3E;Manh&#xE3;&#x3C;/li&#x3E;
                            &#x3C;li&#x3E;Noite&#x3C;/li&#x3E;
                        &#x3C;/ol&#x3E;
                    &#x3C;/li&#x3E;
                    &#x3C;li&#x3E;Curso T&#xE9;cnico em Turismo
                        &#x3C;ol&#x3E;
                            &#x3C;li&#x3E;Manh&#xE3;&#x3C;/li&#x3E;
                            &#x3C;li&#x3E;Noite&#x3C;/li&#x3E;
                        &#x3C;/ol&#x3E;
                    &#x3C;/li&#x3E;
                &#x3C;/ol&#x3E;
                &#x3C;a href=&#x22;#topo&#x22;&#x3E;Volta ao In&#xED;cio&#x3C;/a&#x3E;&#x3C;br&#x3E;
                &#x3C;!-- 4a &#xE2;ncora --&#x3E;
                &#x3C;hr&#x3E;
                &#x3C;a name=&#x22;LANO&#x22;&#x3E;&#x3C;/a&#x3E;
                &#x3C;h2 align=&#x22;center&#x22;&#x3E;Lista Aninhada N&#xE3;o Ordenada&#x3C;/h2&#x3E;
                &#x3C;hr&#x3E;
                &#x3C;ul&#x3E;
                    &#x3C;li&#x3E;Curso T&#xE9;cnico em Eletr&#xF4;nica
                        &#x3C;ul&#x3E;
                            &#x3C;li&#x3E;Manh&#xE3; n&#xE3;o tem&#x3C;/li&#x3E;
                            &#x3C;li&#x3E;Noite&#x3C;/li&#x3E;
                        &#x3C;/ul&#x3E;
                    &#x3C;/li&#x3E;
                    &#x3C;li&#x3E;Curso T&#xE9;cnico em Qu&#xED;mica
                        &#x3C;ul&#x3E;
                            &#x3C;li&#x3E;Manh&#xE3; n&#xE3;o tem&#x3C;/li&#x3E;
                            &#x3C;li&#x3E;Noite&#x3C;/li&#x3E;
                        &#x3C;/ul&#x3E;
                    &#x3C;/li&#x3E;
                &#x3C;/ul&#x3E;
                &#x3C;a href=&#x22;#topo&#x22;&#x3E;Volta ao In&#xED;cio&#x3C;/a&#x3E;&#x3C;br&#x3E;
            &#x3C;/body&#x3E;
            &#x3C;/html&#x3E;
        </pre>
        <br>
        <hr>

        <h1 align="center">Utilizando Âncoras</h1>
        <h3 align="center">
            <font color="white">Nome, Número e Turma dos Integrantes</font>
        </h3>
        <a name="topo"></a>
        <a href="#LO">Lista Ordenada</a><br>
        <a href="#LNO">Lista Não Ordenada</a><br>
        <a href="#LAO">Lista Aninhada Ordenada</a><br>
        <a href="#LANO">Lista Aninhada Não Ordenada</a>
        <hr>
        <a name="LO"></a>
        <h2 align="center">Lista Ordenada</h2>
        <hr>
        <ol>
            <li>Curso Técnico em Informática</li>
            <li>Curso Técnico em Turismo</li>
        </ol>
        <a href="#topo">Volta ao Início</a><br>
        <hr>
        <a name="LNO"></a>
        <h2 align="center">Lista Não Ordenada</h2>
        <hr>
        <ul>
            <li>Curso Técnico em Eletrônica</li>
            <li>Curso Técnico em Química</li>
        </ul>
        <a href="#topo">Volta ao Início</a><br>
        <hr>
        <a name="LAO"></a>
        <h2 align="center">Lista Aninhada Ordenada</h2>
        <hr>
        <ol>
            <li>Curso Técnico em Informática
                <ol>
                    <li>Manhã</li>
                    <li>Noite</li>
                </ol>
            </li>
            <li>Curso Técnico em Turismo
                <ol>
                    <li>Manhã</li>
                    <li>Noite</li>
                </ol>
            </li>
        </ol>
        <a href="#topo">Volta ao Início</a><br>
        <!-- 4a âncora -->
        <hr>
        <a name="LANO"></a>
        <h2 align="center">Lista Aninhada Não Ordenada</h2>
        <hr>
        <ul>
            <li>Curso Técnico em Eletrônica
                <ul>
                    <li>Manhã não tem</li>
                    <li>Noite</li>
                </ul>
            </li>
            <li>Curso Técnico em Química
                <ul>
                    <li>Manhã não tem</li>
                    <li>Noite</li>
                </ul>
            </li>
        </ul>
        <a href="#topo">Volta ao Início</a><br>
    </div>
</template>
  
<script>
export default {
    name: 'Exercise06',
}
</script>

<style scoped></style>