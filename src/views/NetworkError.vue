<template>
  <div class="networkError">
    <h1>Uh-Oh!</h1>
    <h3>
      Its look like network issues
      <a href="#" @click="$router.go(-1)">click here</a>to try again.
    </h3>
  </div>
</template>

<script>
export default {
  props: {
    resource: {
      type: String,
      required: true,
      default: 'page'
    }
  }
}
</script>
