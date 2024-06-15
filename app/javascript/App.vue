<template>
    <Header></Header>
    <nav id="menubar">
        <ul>
            <li><a href="#">HOME</a></li>
            <li><a href="#">COMPANY</a></li>
            <li><a href="#">SERVICE</a></li>
            <li><a href="#">CONTACT</a></li>
            <li><a href="#">CONTACT</a></li>
        </ul>
    </nav>
</template>
  
<script lang="ts">
import { defineComponent } from 'vue'
import Header from "./components/Header.vue";

export default defineComponent({
    components: {
        Header
    }
})
</script>
