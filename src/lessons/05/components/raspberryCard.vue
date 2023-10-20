<template>
  <div class="card">
    <p class="description">{{ description }}</p>
  </div>
</template>

<script>
export default {
  props: {
    description: String
  }
}
</script>

<style scoped>
.card {
  display: flex;
  flex-direction: column;
  width: 200px;
  height: 200px;
  border: 1px dotted blue;
  background-color: white;
  border-radius: 10px;
}
.img-thumb {
  width: 150px;
  height: 150px;
}
.img-thumb > img {
  display: block;
  height: 100%;
  width: 100%;
  object-fit: cover;
  border-top-left-radius: 10px;
}
.company-details {
  display: flex;
  align-items: center;
  padding-top: 5px;
  padding-left: 5px;
}
.logo-thumb {
  width: 20px;
  height: 20px;
  margin-right: 10px;
}
.logo-thumb > img {
  display: block;
  height: 100%;
  width: 100%;
  object-fit: cover;
}
.company-title {
  margin: 0;
}
.description {
  margin: 0;
  padding-left: 5px;
}
</style>
