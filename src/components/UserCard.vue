<template>
  <div class="user-card">
    <img :src="img">
    <h6> {{ firstname + lastname }}</h6>
  </div>
</template>
<script>
export default {
  props:[
      'img',
      'firstname',
      'lastname'
  ]
}
</script>
<style scoped>
.user-card img{
  width: 100%;
  height: 240px;
  border-radius: 4px;
  object-fit: cover;
}
.user-card h6{
  font-size: 20px;
  margin-top: 8px;
}
</style>
