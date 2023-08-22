<template>
    <form>
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome" required><br>

        <label>Gênero:</label>
        <input type="checkbox" id="sexoM" name="sexo" value="M">
        <label for="sexoM">Masculino</label>
        <input type="checkbox" id="sexoF" name="sexo" value="F">
        <label for="sexoF">Feminino</label><br>

        <label for="estadoCivil">Estado Civil:</label>
        <select id="estadoCivil" name="estadoCivil">
            <option value="solteiro">Solteiro</option>
            <option value="casado">Casado</option>
            <option value="outros">Outros</option>
        </select><br>

        <button type="submit">Enviar</button>
    </form>
</template>
  
<script>
export default {
    name: 'Exercise08',
}
</script>

<style scoped></style>