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
     <div class="bg-dark">
        <div class="contentContainer container ">
        <h3 class="text-white">{{ text }}</h3>
    </div>
    </div>
</template>


<style lang="scss" scoped>
    .contentContainer {
        height: 100px;
        display: flex;
        align-items: center;
    }
</style>