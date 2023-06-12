<script setup>
const props = defineProps({
    text: String
})
</script>

<template>
    <button>{{ props.text }}</button>
</template>

<style scoped>
button {
    background-color:rgba(92, 30, 30, 0.842);
    color: #fff;
    border: none;
    border-radius: 5px;
    padding: 10px;
    font-size: 1.0rem;
    cursor: pointer;
    margin: 5px;
}

button:hover{
    background-color:rgba(129, 51, 51, 0.842);
    color: black;
}
</style>