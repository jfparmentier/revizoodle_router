<template>
  <div class="container" align="justify" style="margin-top: 1em">
    <div class="row">
      <div class="two-thirds column">
        <h4 style="margin-bottom: 1em" >Mes cours</h4>
      </div>
      <div class="one-third column">
        <button class="button-primary u-full-width">Importer</button>
      </div>
    </div>

<!--    <p>Vous n'avez créé aucune classe.</p>-->
<!--    &lt;!&ndash; contenu généré dynamiquement par la fonction affichePageQuestionnaires (affichePageQuestionnaires.js) &ndash;&gt;-->
<!--    <p><em>Une classe est un ensemble de questionnaires auxquels devront répondre un groupe d'étudiants.</em></p>-->

    <hr />
    <table class="u-full-width">
      <tbody>
      <tr>
        <th>Aérodynamique</th>
        <td style="text-align: right;">13/01/2021</td>
        <td style="text-align: right;"><router-link class="bouton-avance" to="/enseignant/cours">&gt;</router-link></td>
      </tr>
      <tr>
        <th>Introduction mécanique L1</th>
        <td style="text-align: right;">01/09/2020</td>
        <td style="text-align: right;"><router-link class="bouton-avance" to="/enseignant/classe">&gt;</router-link></td>
      </tr>
      </tbody>
    </table>

    <hr />

  </div>

</template>

<script>
export default {
  name: "Enseignant"
}
</script>

<style scoped>

</style>