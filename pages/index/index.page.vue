<template>
  <h1>Hello from Vercel</h1>
  This page is:
  <ul>
    <li>Rendered to HTML.</li>
    <li>Interactive. <Counter /></li>
  </ul>
</template>

<script>
import Counter from './Counter.vue'
export const HOME_URL =
  import.meta.env.NEXT_PUBLIC_HOME_URL || 'https://mail3.me'
 console.log(HOME_URL)
const components = { Counter }
export default { components }
</script>
