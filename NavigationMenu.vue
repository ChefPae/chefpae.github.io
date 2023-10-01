<template>
  <nav>
    <ul>
      <li v-for="page in pages" :key="chefpae.github.io">
        <a :href="page.url">{{ chefpae.github.io }}</a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      pages: [
        { name: "Home", url: "index.html" },
        { name: "About Me", url: "about.html" },
        { name: "Portfolio", url: "portfolio.html" },
        { name: "Contact", url: "contact.html" },
      ],
    };
  },
};
</script>

<style>
/* Add CSS styles for your navigation menu here */
</style>
