<template>
  <div class="card text-center">
    <div class="card-header">
      Featured
    </div>
    <div class="card-body">
      <h5 class="card-title">Special title treatment</h5>
      <img class="card-img-top" :src="info" />
      <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
    <div class="card-footer text-muted">
      2 days ago
    </div>
  </div>
</template>

<script>
export default {
  props: ["info"],
  name: "BookCard",
};
</script>
