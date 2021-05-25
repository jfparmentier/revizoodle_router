<template>
  <div class="container" align="justify" style="margin-top: 1em">
    <div class="row">
      <div class="two-thirds column">
        <h4 style="margin-bottom: 1em" >Mes cours</h4>
      </div>
      <div class="one-third column">
        <button class="button-success u-full-width">Rejoindre</button>
      </div>
    </div>

    <hr />
    <table class="u-full-width">
      <tbody>
      <tr>
        <th>Aérodynamique</th>
        <td style="text-align: right;">13/01/2021</td>
        <td style="text-align: right;"><router-link class="bouton-avance" to="/etudiant/classe">&gt;</router-link></td>
      </tr>
      <tr>
        <th>Introduction mécanique L1</th>
        <td style="text-align: right;">01/09/2020</td>
        <td style="text-align: right;"><router-link class="bouton-avance" to="/etudiant/classe">&gt;</router-link></td>
      </tr>
      </tbody>
    </table>

    <hr />
  </div>
</template>

<script>
export default {
  name: "Etudiant"
}
</script>

<style scoped>

</style>