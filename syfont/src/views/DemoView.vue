<template>
    <div class="about">
        <h1>{{msg}} This is an Demo page</h1>
        <span>{{msg}}</span>
        <h1 v-text="msg"></h1>

    </div>
</template>
<script>
export default {
    name: 'DemoView',
    msg: "YOU Will OK!",
    components: {
        
    }
}

</script>
<style scoped>
    
</style>
