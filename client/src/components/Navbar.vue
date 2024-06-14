<script setup lang="ts">
import { RouterLink } from 'vue-router';
import signiture from './icons/signature.png';
</script>

<template>
    <ul class="menu">
        <li>
            <a>Menu</a>

            <ul>
                    <li><a><RouterLink to="/">SELECTED WORKS</RouterLink></a></li>
                
                    <li><a><RouterLink to="/about">ABOUT</RouterLink></a></li>
                    <li><a><RouterLink to="/contact">CONTACT</RouterLink></a></li>
            </ul>
        </li>
    </ul>
    <h1 class="Title">CAEVEAR</h1>
    <h2 class="Name">Vicky</h2>
    <!-- <div class="navbar-start">
            <router-link to="/">
                <img :src="signiture" class="signiture" alt="Signature">
            </router-link>
        </div> -->
</template>


<style scoped>
.menu {
    display: block;
    margin: 0 auto;
    position: relative;
    width: 200px;
}

.menu>li>a {
    color: #919191;
    font-family: europa, sans-serif;
    font-weight: 300;
    font-style: normal;
    line-height: 1.8em;
    letter-spacing: .04em;
    font-size: 14px;
    display: block;
    padding: 10px 20px;
    text-align: center;
    text-decoration: none;
}

.menu ul {
    text-align: center;
    background: #fcfcfc;
    height: 0;
    left: 50%;
    opacity: 0;
    position: absolute;
    transition: all .5s ease;
    top: 35px;
    width: 400px;
    width: 100%;
    transform: translateX(-50%);
}

.menu li:hover ul {
    height: 200px;
    width: 300px;
    opacity: 1;
    transform: translateY(0) translateX(-50%);
}

.menu ul a {
    color: #919191;
    font-size: 16px !important;
    line-height: 2.5em !important;
    letter-spacing: 0px;
    font-family: brandon-grotesque;
    font-weight: 400;
    font-style: normal;
    text-transform: none;
    font-size: 14px;
    letter-spacing: .06em;
    display: block;
    padding: 5px 20px;
}

.Title {
    margin-top: 5rem;
    text-align: center;
    color: black;
    font-family: "Cormorant", Sans-serif;
    font-size: 40px;
    font-weight: 1000;
}

.Name {
    text-align: center;
    margin-top: .4rem;
    color: rgb(0, 0, 0);
    font-family: "Montserrat", Sans-serif;
    font-size: 14px;
    font-weight: 540;
    text-transform: uppercase;
    letter-spacing: 1.9px;
}

/* .signiture {
    margin-top: 20px;
    margin-left: 40px;
    width: 60%;
}

@media screen and (max-width: 768px) {
    .signiture {
        width: 30%;
    }
} */
</style>