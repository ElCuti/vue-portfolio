<script setup>
const navItems = [
  { id: 'inicio', label: 'Inicio' },
  { id: 'tecnologias', label: 'Tecnologías' },
  { id: 'proyectos', label: 'Proyectos' },
  { id: 'sobre-mi', label: 'Sobre mí' },
  { id: 'contacto', label: 'Contacto' },
]
</script>

<template>
  <header class="sticky top-0 border-b border-slate-800">
    <nav class="flex justify-between px-6 py-4">
      <a href="#inicio" class="text-lg font-bold text-slate-900">Daniel Cutillas Cremades</a>

      <ul class="flex gap-5">
        <li v-for="item in navItems" :key="item.id">
          <a :href="`#${item.id}`" class="text-sm text-slate-800 hover:underline">
            {{ item.label }}
          </a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
a {
  font-family: 'Edu QLD Hand';
}
</style>
