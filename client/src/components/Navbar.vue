<script setup lang="ts">
import { RouterLink } from 'vue-router';
import signiture from './icons/signature.png';
</script>

<template>
    <nav class="navbar" role="navigation" aria-label="main navigation">
        <div class="navbar-start">
            <router-link to="/">
                <img :src="signiture" class="signiture" alt="Signature">
            </router-link>
        </div>
    </nav>
</template>


<style scoped>
.signiture {
    margin-top: 20px;
    margin-left: 40px;
    width: 60%;
}

@media screen and (max-width: 768px) {
    .signiture {
        width: 30%;
    }
}
</style>