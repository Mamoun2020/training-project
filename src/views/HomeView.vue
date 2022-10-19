<template>
  <div class="container mt-4">
    <div class="row">
      <div class="col-md-2">
        <UserCard/>
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