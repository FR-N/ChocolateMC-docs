<template>
  <div>
    <h2>Theme Data</h2>
    <pre>{{ theme }}</pre>
    <h2>Page Data</h2>
    <pre>{{ page }}</pre>
    <h2>Page Frontmatter</h2>
    <pre>{{ frontmatter }}</pre>
  </div>
</template>

<script setup>
import { useData } from 'vitepress'
const { theme, page, frontmatter } = useData()
</script>