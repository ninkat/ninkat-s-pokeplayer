<template>
    <div :key="task.id" v-for="task in tasks">
        <myTask :task="task" />
    </div>
</template>

<script>
import myTask from './Task.vue'
    export default {
        name: "myTasks",
        props: {
            tasks: Array
        },
        components: {
            myTask,
        }
    }
</script>