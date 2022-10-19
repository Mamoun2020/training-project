<template>
  <div class="container mt-4">
    <div class="row">
      <div class="col-md-2">
        <UserCard img="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7e/Circle-icons-profile.svg/2048px-Circle-icons-profile.svg.png" firstname="mamoun" lastname="kamal"/>
      </div>
    </div>
  </div>
</template>

<script>
import UserCard from "../components/UserCard.vue";
export default {
  components: {UserCard}
}
</script>