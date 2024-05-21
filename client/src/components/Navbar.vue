<script setup lang="ts">
import { RouterLink } from 'vue-router';
import signiture from './icons/signature.png';
</script>

<template>
    <nav class="navbar" role="navigation" aria-label="main navigation">
        <div id="navbarBasicExample" class="navbar-menu">
            <div class="navbar-start">
                <router-link to="/">
                    <img href="/" class="signiture" :src="signiture" alt="Signature" />
                </router-link>
            </div>
        </div>
    </nav>
</template>

<style scoped>
.navbar {
    background-color: white;
}

.signiture {
    margin-top: 20px;
    margin-left: 40px;
    width: 180px;
}
</style>