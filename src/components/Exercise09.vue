<template>
    <table border="1">
        <tr>
            <td>Usuário:</td>
            <td><input type="text" id="usuario" name="usuario" required></td>
        </tr>
        <tr>
            <td>Senha:</td>
            <td><input type="password" id="senha" name="senha" required></td>
        </tr>
        <tr>
            <td colspan="2" align="center">
                <button type="submit">Enviar</button>
            </td>
        </tr>
    </table>
</template>
  
<script>
export default {
    name: 'Exercise09',
}
</script>

<style scoped></style>