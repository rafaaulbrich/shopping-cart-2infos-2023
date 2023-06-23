<script setup>
const props = defineProps({
    text: String
})
</script>

<template>
    <button>
        <slot>
            {{ props.text }}
        </slot>
    </button>
</template>

<style scoped>
/* button {
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
} */

button{
    border-radius: 3px;
    border: 1px solid #6c757d;
}
.primario {
  background-color: #007bff;
}
.primario:hover {
  background-color: #0069d9;
}

.secundario {
  background-color: #6c757d;
}
.secundario:hover {
  background-color: #5a6268;
}

.terciario {
  background-color: #28a745;
}
.terciario:hover {
  background-color: #218838;
}

.perigo {
  background-color: #dc3545;
}
.perigo:hover {
  background-color: #c82333;
}
.alerta {
  background-color: #ffc107;
}
.alerta:hover {
  background-color: #e0a800;
}
.sucesso {
  background-color: #28a745;
}
.sucesso:hover {
  background-color: #218838;
}
.info {
  background-color: #17a2b8;
}
.info:hover {
  background-color: #138496;
}
.escuro {
  background-color: #343a40;
}
.escuro:hover {
  background-color: #23272b;
}
.claro {
  background-color: #f8f9fa;
}
.claro:hover {
  background-color: #dae0e5;
}
</style>