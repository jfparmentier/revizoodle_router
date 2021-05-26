<template>
<div class="container" align="justify" style="margin-top: 1em">

  <h5><router-link to="/etudiant" class="bouton-retour">&lt;</router-link></h5>
  <h5 style="text-align:center">Mécanique rationnelle</h5>

  <hr />
  <table class="u-full-width">
    <tbody>
    <tr>
      <th>Principes fondamentaux</th>
      <td style="text-align: right;">Score : 70%</td>
    </tr>
    </tbody>
  </table>
  <div class="row">
    <div class="two-thirds column">
      <table class="u-full-width">
        <tbody>
        <tr>
          <td>27/03/2020</td>
          <td>12 questions</td>
        </tr>
        </tbody>
      </table>
    </div>
    <div class="one-third column" style="vertical-align: middle;">
      <button class="button-primary u-full-width"><router-link to="/etudiant/question" style="text-decoration: none; color: #fff">Refaire</router-link></button>
    </div>
  </div>

  <hr />
  <table class="u-full-width">
    <tbody>
    <tr>
      <th>Matrices d'inertie</th>
      <td style="text-align: right;"><strong>Incomplet</strong></td>
    </tr>
    </tbody>
  </table>
  <div class="row">
    <div class="two-thirds column">
      <table class="u-full-width">
        <tbody>
        <tr>
          <td>27/03/2020</td>
          <td>12 questions</td>
        </tr>
        </tbody>
      </table>
    </div>
    <div class="one-third column" style="vertical-align: middle;">
      <button class="button-warning u-full-width"><router-link to="/etudiant/question" style="text-decoration: none; color: #fff">Continuer</router-link></button>
    </div>
  </div>

  <hr />
</div>
</template>

<script>
export default {
  name: "CoursEtudiant"
}
</script>

<style scoped>

</style>