<template>
  <div class="options-container">
    <ul>
      <li>Charmander</li>
      <li>Bulbasor</li>
      <li>Goku</li>
      <li>Pikachu</li>
    </ul>
  </div>
</template>

<script setup>

</script>
<style scoped>
ul {
  list-style-type: none;
}

li {
  background-color: white;
  border-radius: 5px;
  border: 1px solid rgba(0, 0, 0, 0.2);
  cursor: pointer;
  margin-bottom: 10px;
  width: 250px;
  padding: 3px;
}

li:hover {
  background-color: rgba(0, 0, 0, 0.05);
}

.options-container {
  display: flex;
  justify-content: center;
}
</style>
