<template>
  <div class="container">
    <RecipePreviewList title="My Recipes" kind="my" class="RandomRecipes center" />
  </div>
</template>

<script>
import RecipePreviewList from "../components/RecipePreviewList";
export default {
components: {
  RecipePreviewList
}
};
</script>

<style scoped>
  .container {
      margin-top: 100px;
      font-family: 'Calibri Light', 'Calibri';
  }
  .RandomRecipes {
      margin: 100px 0 10px;
  }
</style>