<template>
  <table>
    <caption>
      Catálogo de Protudos - Desenvolvimento WEB I
    </caption>
    <thead>
      <tr>
        <th>Protudos</th>
        <th class="custom-width">Categoria</th>
        <th class="custom-width">Preço</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>
          <a href="https://google.com">
            Faça Você Mesmo: Comida Japonesa
          </a>
        </td>
        <td>DVD</td>
        <td>55</td>
      </tr>
      <tr>
        <td>
          <a href="https://google.com">
            Faça Você Mesmo: Comida Mexicana
          </a>
        </td>
        <td>DVD</td>
        <td>42</td>
      </tr>
      <tr>
        <td>
          <a href="https://google.com">
            Faça Você Mesmo: Comida Árabe
          </a>
        </td>
        <td>DVD</td>
        <td>39</td>
      </tr>
    </tbody>
  </table>
</template>

<script>
export default {
  name: 'ProductTable',
}
</script>

<style scoped>
caption {
  background-color: black;
  color: white;
  font-weight: 600;
  padding: 20px 0;
}
th {
  background-color: #858495;
  color: white;
  font-weight: 400;
}
th.custom-width {
  width: 125px;
}
td, td > a {
  color: #858495;
}
table {
  border-spacing: 5px;
}
</style>