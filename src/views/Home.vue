<template>
  <div>
    <Menu></Menu>
    <div class="container mt-4">
      <h1 class=mb-4>Home Page</h1>
      <p>Documentation and examples for Bootstrap’s powerful, responsive navigation header, the navbar. Includes support for branding, navigation, and more, including support for our collapse plugin.</p>
    </div>
    <Footer></Footer>
  </div>
</template>

<script>
// @ is an alias to /src

import Menu from "@/components/Menu.vue";
import Footer from "@/components/Footer.vue";
export default {
  name: "Home",
  components: {
    Menu,
    Footer
  },
};
</script>
