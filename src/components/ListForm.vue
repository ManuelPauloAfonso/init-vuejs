<script setup>


</script>


<template>
  <div class="todo-list">
      <h2>Lista de Tarefas</h2>
      <ul id="taskList">
        <li>
          <div class="task-info">
            <span>Tarefa:</span>
            <span>Fazer compras</span>
          </div>
          <div class="actions">
            <button class="edit-btn">Editar</button>
            <button class="delete-btn">Apagar</button>
          </div>
        </li>
        <li>
          <div class="task-info">
            <span>Tarefa:</span>
            <span>Lavar o carro</span>
          </div>
          <div class="actions">
            <button class="edit-btn">Editar</button>
            <button class="delete-btn">Apagar</button>
          </div>
        </li>
      </ul>
    </div>

</template>



<style scoped>
/* Estilos básicos para a lista de tarefas */
.todo-list {
  margin-bottom: 1rem;
}

.todo-list h2 {
  font-size: 1.5rem;
  margin-bottom: 0.5rem;
}

.todo-list ul {
  list-style-type: none;
  padding: 0;
}

.todo-list li {
  margin-bottom: 0.5rem;
}

.task-info {
  font-weight: bold;
}

.task-info span {
  margin-right: 0.5rem;
}

.actions {
  display: flex;
  gap: 0.5rem;
}
</style>