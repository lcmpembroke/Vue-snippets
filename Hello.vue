<template>
    <p> {{ greeting }} World! </p>
</template>

<<script>
module.exports = {
    data: function () {
        return {
            greeting: 'Hello greeting in Hello.vue'
        }
    }
}
</script>

<style scoped>
p {
    font-size: 2em;
    text-align: center;
}
    
</style>