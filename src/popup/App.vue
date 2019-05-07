<template>
  <table id="tabela">
    <tr class="linha">
      <td class="coluna1">Esta é uma célula</td>
      <td class="coluna2">Esta é uma célula</td>
      <td class="coluna3">Esta é uma célula</td>
    </tr>
    <tr class="linha">
      <td class="coluna1">Esta é uma célula</td>
      <td class="coluna2">Esta é uma célula</td>
      <td class="coluna3">Esta é uma célula</td>
    </tr>
    <tr class="linha">
      <td class="coluna1">Esta é uma célula</td>
      <td class="coluna2">Esta é uma célula</td>
      <td class="coluna3">Esta é uma célula</td>
    </tr>
    <tr class="linha">
      <td class="coluna1">Esta é uma célula</td>
      <td class="coluna2">Esta é uma célula</td>
      <td class="coluna3">Esta é uma célula</td>
    </tr>
    <tr class="linha">
      <td class="coluna1">Esta é uma célula</td>
      <td class="coluna2">Esta é uma célula</td>
      <td class="coluna3">Esta é uma célula</td>
    </tr>
  </table>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style lang="scss" scoped>
p {
  font-size: 20px;
}

#tabela,
table,
tr,
td {
  border: 1px solid black;
}

#tabela {
  font-family: SFMono-Regular, Menlo, Monaco, Consolas, 'Liberation Mono', 'Courier New', monospace;
  text-align: center;
  font-size: large;
}
</style>
