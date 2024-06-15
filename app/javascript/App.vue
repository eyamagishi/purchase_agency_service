<template>
    <header>
        <h1 id="logo"><a href="#">{{ state.message }}</a></h1>
    </header>
</template>
  
<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    name: 'App',
    setup() {
        return {
            state: {
                message: "SAMPLE 株式会社"
            }
        }
    }
})
</script>
  
<style scoped>
p {
    font-size: 2em;
    text-align: center;
}
</style>
