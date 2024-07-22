<script>
import {  useNav } from '@slidev/client'

const { currentSlideNo } = useNav()

</script>

<template>
  <p>
    currentSlideNo from useNav(): {{ currentSlideNo }} |
  </p>
</template>