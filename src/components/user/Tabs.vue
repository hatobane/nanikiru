<template>
  <ul class="m-tabs">
    <li :class="{active:mode===1}" @click="$emit('change', 1)">NANIKIRU</li>
    <li :class="{active:mode===2}" @click="$emit('change', 2)">Answer</li>
    <li :class="{active:mode===3}" @click="$emit('change', 3)"><i class="icon-star"></i></li>
  </ul>
</template>

<script>
export default {
  props: ['mode']
}
</script>