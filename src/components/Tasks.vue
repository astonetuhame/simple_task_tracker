<template>
    <div v-for="(task, index) in tasks" :key="index">
        <h3>{{ task.text}}</h3>
    </div>
</template>


<script>
export default {
    name: "Tasks",
    props: {
        tasks: Array
    }
}
</script>