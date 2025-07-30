<script setup >
import { ref } from 'vue';

const count = ref(0);

const incriment = () =>{
  count.value++;
}
</script>


<template>
<div>
    <h1>Counter </h1>
    <p>count: {{ count }}</p>
    <button @click ="incriment"> + </button>
</div>
</template>


<style>

</style>