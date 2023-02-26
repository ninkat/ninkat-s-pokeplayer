<template>
    <header>
        <h1>{{ title }}</h1>
        <myButton text = "Add Log" color="green" />
    </header>
</template>

<script>
import myButton from './Button.vue'

export default {
    name: 'myHeader',
    props: {
        title: String,
    },
    components: {
        myButton,
    },
}
</script>

<style scoped>
header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
}
</style>