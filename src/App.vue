<template>
  <HeaderMenu />
  <main>
    <PokemonTodos />
  </main>
</template>

<script setup>
import PokemonTodos from "./components/PokemonTodos.vue";
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Rubik:wght@300;400;500;600;700;800;900&display=swap");

:root {
  --clr-black: #1c1c1c;
  --clr-gray: #414040;
  --clr-white: #f7f7f7;

  --type-normal: #a8a878;
  --type-fire: #f08030;
  --type-water: #6890f0;
  --type-grass: #78c850;
  --type-electric: #f8d030;
  --type-ice: #98d8d8;
  --type-fighting: #c03028;
  --type-poison: #a040a0;
  --type-ground: #e0c068;
  --type-flying: #a890f0;
  --type-psychic: #f85888;
  --type-bug: #a8b820;
  --type-rock: #b8a038;
  --type-ghost: #705898;
  --type-dark: #705848;
  --type-dragon: #7038f8;
  --type-steel: #b8b8d0;
  --type-fairy: #f0b6bc;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  color: var(--clr-white);
  font-family: "Rubik", sans-serif;
}

ul {
  list-style-type: none;
}

button {
  background-color: transparent;
  border: 0;
  border-radius: 0;
}

/* Aquí todo el CSS extra */
body {
  min-height: 100vh;
  background-color: var(--clr-black);
}

main {
  padding: 2rem;
  max-width: 1000px;
  margin: 0 auto;
}
/* Aquí comienzan los colores de botones según tipo */
.normal {
  background-color: var(--type-normal);
  color: var(--clr-black);
}

.fire {
  background-color: var(--type-fire);
  color: var(--clr-black);
}

.water {
  background-color: var(--type-water);
  color: var(--clr-white);
}

.grass {
  background-color: var(--type-grass);
  color: var(--clr-black);
}

.electric {
  background-color: var(--type-electric);
  color: var(--clr-black);
}

.ice {
  background-color: var(--type-ice);
  color: var(--clr-black);
}

.fighting {
  background-color: var(--type-fighting);
  color: var(--clr-white);
}

.poison {
  background-color: var(--type-poison);
  color: var(--clr-white);
}

.ground {
  background-color: var(--type-ground);
  color: var(--clr-black);
}

.flying {
  background-color: var(--type-flying);
  color: var(--clr-black);
}

.psychic {
  background-color: var(--type-psychic);
  color: var(--clr-black);
}

.bug {
  background-color: var(--type-bug);
  color: var(--clr-black);
}

.rock {
  background-color: var(--type-rock);
  color: var(--clr-black);
}

.ghost {
  background-color: var(--type-ghost);
  color: var(--clr-white);
}

.dark {
  background-color: var(--type-dark);
  color: var(--clr-white);
}

.dragon {
  background-color: var(--type-dragon);
  color: var(--clr-white);
}

.steel {
  background-color: var(--type-steel);
  color: var(--clr-black);
}

.fairy {
  background-color: var(--type-fairy);
  color: var(--clr-black);
}
</style>
