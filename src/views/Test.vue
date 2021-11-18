<template>
    <h1>hello {{word}}</h1>
</template>

<script lang="ts">
    import { defineComponent , ref, reactive, onMounted } from 'vue';
    const Test = defineComponent({
        setup() {
            let word: string = 'world'
            return {
                word
            }
        }
    })
    export default Test;
</script>

<style scoped>

</style>