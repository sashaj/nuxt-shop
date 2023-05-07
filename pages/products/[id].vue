<template>
  <div>
    <h2>product details for {{ useRoute() }}</h2>
    <h2>product details for {{ id }}</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus
      similique quaerat labore. Quo placeat, iste aperiam fuga sit, minus
      tenetur molestiae, dicta cum commodi dignissimos voluptatem optio unde
      fugiat. Repellendus?
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus
      similique quaerat labore. Quo placeat, iste aperiam fuga sit, minus
      tenetur molestiae, dicta cum commodi dignissimos voluptatem optio unde
      fugiat. Repellendus?
    </p>
  </div>
</template>

<script setup>
const id = useRoute().params.id;
definePageMeta({
  layout: "products",
});
</script>

<style scoped></style>
