<script setup>
    import { ref } from 'vue'

    const text= ref ('Shopping list')
    const show = ref(true)
    const list = ref([1, 2, 3])
</script>


<template>
    <h1> {{ text }}</h1>


    <button @click="show = !show">New item</button>
    

</template>