<script setup lang="ts">
</script>

<template>
    <div>
        <div class="columns is-mobile">
            <div class="column"></div>
            <div class="column is-four-fifths">
                <div class="Images">
                    <img src="../assets/images/1.jpg" />
                </div>
                <div class="Images">
                    <img src="../assets/images/2.jpg" />
                </div>
                <div class="Images">
                    <img src="../assets/images/3.jpg" />
                </div>
                <div class="Images">
                    <img src="../assets/images/4.jpg" />
                </div>
            </div>
            <div class="column"></div>
        </div>
    </div>
</template>

<style scoped>


.Images {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.Images img {
    width: 100%;
    height: auto;
}
</style>