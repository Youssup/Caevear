<script setup lang="ts">
</script>

<template>
    <div>
        <h1 class="Title">Oil paintings and charcoal drawings</h1>
        <h2 class="Name">By Vicky Wong</h2>
        <div class="columns is-mobile">
            <div class="column"></div>
            <div class="column is-four-fifths">
                <div class="Images">
                    <img src="../assets/images/3.jpg" />
                    <h4>Abstract 1</h4>
                    <h5>28&quot;x28&quot;</h5>
                    <img src="../assets/images/1.jpg" />
                    <h4>Still Life 1</h4>
                    <h5>18&quot;x24&quot;</h5>
                    <img src="../assets/images/2.jpg" />
                    <h4>Still Life 2</h4>
                    <h5>18&quot;x24&quot;</h5>
                </div>
            </div>
            <div class="column"></div>
        </div>
        <div class="InfoContainer">
            <h1 class="Info">Email</h1>
            <a href="https://mail.google.com/mail/?view=cm&fs=1&to=caevear@gmail.com" class="Redirect"
                target="_blank">caevear@gmail.com</a>
            <h1 class="Info">Instagram</h1>
            <a href="https://www.instagram.com/caevear/?hl=en" class="Redirect" target="_blank">@caevear</a>
        </div>
    </div>
</template>

<style scoped>
.Title {
    margin-top: 5rem;
    text-align: center;
    color: black;
    font-family: "Cormorant", Sans-serif;
    font-size: 40px;
    font-weight: 600;
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

.Images {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 7rem;
}

.Images img {
    margin: 2rem;
    width: 100%;
    height: auto;
}

.Images h4 {
    width: 100%;
    text-align: left;
    margin-top: 1.5rem;
    font-family: "Montserrat", Sans-serif;
    font-size: 30px;
    font-weight: 500;
    text-transform: uppercase;
    letter-spacing: 1.9px;
}

.Images h5 {
    width: 100%;
    text-align: left;
    margin-top: 1rem;
    font-family: "Cormorant", Sans-serif;
    font-size: 30px;
    font-weight: 550;
    line-height: 0.2em;
    letter-spacing: 1.2px;
    margin-bottom: 7rem;
}

.InfoContainer {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 6rem;
}
.Info {
    color: black;
    font-family: "Montserrat", Sans-serif;
    font-size: 12px;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 1.9px;
}

.Redirect {
    color: black;
    font-family: "Montserrat", Sans-serif;
    font-size: 14px;
    font-weight: 400;
    line-height: 1.7em;
}
</style>