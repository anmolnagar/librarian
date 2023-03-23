<template>
    <div>

    <!-- all functions that are globally used are in this file. We need to declare this in main.js -->

    </div>
</template>

<script>
    export default {
    methods: {
        randomColor() {
            return "#"+Math.floor(Math.random() * 0x1000000).toString(16)
        }
    },
}
</script>

<style lang="scss" scoped>
</style>