<template>
  <div class="navBar">
    <div class="elements row">
      <div class="logo col-3"></div>
      <div class="navItems col-6">
        <div v-for="item in navItems" :key="item.name">
          <nuxt-link class="item " :to="item.route">{{item.name}}</nuxt-link>
        </div>
      </div>
      <div class="socials col-3">
          <p>Retrouvez-nous sur:</p>
          <div class="icons">
            <img class="facebook" src="/icons/logo-facebook.png" alt="logo facebook">
            <img class="leetchi" src="/img/logo-leetchi.png" alt="">
          </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      navItems: [
           {
          name: "Le refuge",
          route: "/Refuge"
        },
        {
          name: "les Chiens",
          route: "Aider le refuge"
        },
     
        {
          name: "Nos actualités",
          route: "/Actualites"
        },
        {
            name: "Démarches",
            route: "/Demarches"
        },
        {
          name: "Nous contacter",
          route: "/Contact"
        },
      ]
    };
  }
};
</script>

