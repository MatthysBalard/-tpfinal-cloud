<script setup>
const buildId = import.meta.env.VITE_BUILD_ID ?? 'local'
const today = new Date().toLocaleDateString('fr-FR')
</script>
<template>
<header>
<p>Nom : Matthys Balard</p>
<p>Date : {{ today }}</p>
<p>Build : {{ buildId }}</p>
</header>
</template>

<style>p{background-color:greenyellow}</style>
