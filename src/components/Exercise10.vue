<template>
    <table border="1">
        <tr>
            <td>Usuário:</td>
            <td><input type="text" id="usuario" name="usuario" required></td>
            <td>Senha:</td>
            <td><input type="password" id="senha" name="senha" required></td>
            <td align="center">
                <button type="submit">Enviar</button>
            </td>
        </tr>
        <tr>
            <td colspan="5" align="center">
                <label><input type="checkbox" id="lembrar" name="lembrar"> Lembrar Usuário e Senha</label>
            </td>
        </tr>
    </table>
</template>
  
<script>
export default {
    name: 'Exercise10',
}
</script>

<style scoped>
table {
    border-collapse: collapse;
}
</style>