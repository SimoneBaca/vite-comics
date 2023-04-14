<script>
    export default {
        name: 'ContentComponent',
        data() {
            return {
                text: '--> Content insert here <--'
            }
        }
    }
</script>

<template>
    <div class="contentContainer container bg-dark">
        <h1 class="text-white">{{ text }}</h1>
    </div>
</template>


<style lang="scss" scoped>
    .contentContainer {
        height: 150px;
        display: flex;
        align-items: center;
    }
</style>