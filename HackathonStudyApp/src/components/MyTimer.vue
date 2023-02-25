<template>
    <b-col>
        <p aria-setsize="10000" >{{ timer }} seconds left.</p>

            <button> Add 1 hours</button>
            <button> Add 30 minutes</button>
            <button> Add 15 minutes</button>
            <button> Add 5 minutes</button>
            <button> Add 1 minute</button>
    </b-col>
    
</template>

<script>
    export default {

        data() {
            return {
                timer: 30
            }
        },
    }

</script>

<style>
p{
    text-align: center;
}
button {
    text-align: center;
}
</style>