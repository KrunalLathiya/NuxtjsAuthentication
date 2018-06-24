<template>
  <div class="container">
    <p v-if="loggedIn">
      Hello {{ user.name }}
    </p>
    <p v-if="!loggedIn">
      Please sign in
    </p>
  </div>
</template>

<script>

export default {
  
}
</script>