<template>
    <table>
        <thead>
            <tr>
                <th colspan="1">Título da Tabela</th>
                <th colspan="2">Coluna 2</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Linhas</td>
                <td colspan="2">Primeira Linha</td>
            </tr>
            <tr>
                <td>Segunda Linha</td>
                <td>Coluna 1</td>
                <td>Coluna 2</td>
            </tr>
        </tbody>
    </table>
</template>
  
<script>
export default {
    name: 'Exercise04',
}
</script>

<style scoped>
table {
    border-collapse: collapse;
    text-align: center;
    border: 1px solid black;
}
th,td {
    border: 1px solid black;
    padding: 10px;
}</style>