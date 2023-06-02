<template>
  <div>
    <h2>about</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus
      similique quaerat labore. Quo placeat, iste aperiam fuga sit, minus
      tenetur molestiae, dicta cum commodi dignissimos voluptatem optio unde
      fugiat. Repellendus?
    </p>

    <p>{{ data }}</p>
  </div>
</template>

<script setup>
const { data } = await useFetch("/api/currency/GBP");
</script>

<style scoped></style>
