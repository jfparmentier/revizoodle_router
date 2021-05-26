<template>
<div class="container" align="justify" style="margin-top: 1em">
  <h5><router-link to="/etudiant/cours" class="bouton-retour">&lt;</router-link></h5>
  <h5 style="text-align:center; margin-top: 2%">Question 1 / 12</h5>
  <span><p>Un moustique s'écrase sur la vitre d'un TGV. Que dire de la force exercée par la vitre sur le moustique, par rapport à la force exercée par le moustique sur la vitre ?</p></span>
  <div>
    <div class="bouton-reponseE u-full-width">la force exercée par la vitre est plus grande</div>
    <div class="bouton-reponseE u-full-width">elles sont égales en norme</div>
    <div class="bouton-reponseE u-full-width">la force exercée par le moustique est plus grande</div>
  </div>
  <hr />
</div>
</template>

<script>
export default {
  name: "QuestionEtudiant"
}
</script>

<style scoped>
.bouton-reponseE {
  display: inline-block;
  padding: 10px 5px;
  margin-bottom: 0.6rem;
  color: #555;
  text-align: center;
  font-size: small;
  text-decoration: none;
  background-color: transparent;
  border-radius: 4px;
  border: 1px solid #bbb;
  cursor: pointer;
  box-sizing: border-box;
}

.bouton-reponseE:hover,
.bouton-reponseE:focus {
  color: #333;
  border-color: #888;
  outline: 0;
}
</style>