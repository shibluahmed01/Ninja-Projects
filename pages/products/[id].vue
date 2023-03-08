<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sint enim vel
      aliquam commodi cupiditate est tempora quidem animi explicabo deleniti!
    </p>
  </div>
</template>
<script setup>
const { id } = useRoute().params;
</script>

<style scoped></style>
