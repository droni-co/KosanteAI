<template>
  <div>
    <header>
      <h1>Mi sitio Nuxt 3</h1>
    </header>
    <main>
      <slot />
    </main>
    <footer>
      <small>© 2025 Mi sitio Nuxt 3</small>
    </footer>
  </div>
</template>

<script setup>
// Puedes agregar lógica global aquí
</script>

<style scoped>
header {
  background: #222;
  color: #fff;
  padding: 1rem;
  text-align: center;
}
main {
  min-height: 60vh;
  padding: 2rem;
}
footer {
  background: #f5f5f5;
  color: #333;
  text-align: center;
  padding: 1rem;
  font-size: 0.9rem;
}
</style>
