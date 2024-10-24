<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/">Nuxt Dojo</NuxtLink>
        <!-- <ul>
          <li><NuxtLink to="/catalog">Nuxt Dojo Merch</NuxtLink></li>

        </ul> -->
      </nav>
    </header>

    <div>
      <slot />
    </div>

    <footer>
      <li><NuxtLink to="/">Home</NuxtLink></li>

      <!-- <li><NuxtLink to="/">Products</NuxtLink></li> -->
    </footer>
  </div>
</template>

<style scoped>
.router-link-exact-active {
  color: green;
}
</style>
