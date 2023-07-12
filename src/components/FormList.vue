<script setup>


</script>


<template>
    <form>
        <input type="text" id="taskInput" placeholder="Digite uma nova tarefa">
        <button type="submit">Enviar</button>
    </form>
</template>



<style scoped>
form {
    margin-bottom: 1rem;
}

input[type="text"] {
    padding: 0.5rem;
    width: 300px;
}

button {
    padding: 0.5rem 1rem;
    background-color: #4CAF50;
    color: white;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}
</style>