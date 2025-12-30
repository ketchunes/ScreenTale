<template>
  <div class="px-10 flex gap-5 pb-5">
    <div v-for="button in buttons">
      <div class="btn bg-accent border-0 py-3 px-6 rounded-3xl transition duration-700 hover:border">{{ button.text }}</div>
    </div>
  </div>
</template>

<script setup>
  const buttons = [
    {
      text: "Action",
    },
    {
      text: "Adventure",
    },
    {
      text: "Comedy",
    },
    {
      text: "Sci-Fi",
    },
    {
      text: "Horror",
    },
    {
      text: "Drama",
    },
    {
      text: "Thriller",
    },
    {
      text: "Fantasy",
    },
    {
      text: "Animation",
    },
  ];
</script>
