<template>
<div>
  <div class="container">
    <div class="cover">
      <img class="cover-image" alt="golden eclipse products" :src="cover">
    </div>
  </div>
  <h1>Bio coming soon!</h1>

</div>
</template>

<script>
export default {
  name: 'Home',
  data() {
    return {
      cover: require('/images/cust_notes.jpg')
    }
  },
}
</script>

<style>
.container {
 display: flex;
 width: 80%;
 margin: 0 auto;
}

.cover {
  max-width:100%;
  max-height:100%;
}

.cover-image {
  width: 100%;
}
</style>
