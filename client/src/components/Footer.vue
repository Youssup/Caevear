<script setup lang="ts">

</script>

<template>
    <div>
        <!-- <div class="InfoContainer">
            <h1 class="Info">Email</h1>
            <a href="https://mail.google.com/mail/?view=cm&fs=1&to=caevear@gmail.com" class="Redirect"
                target="_blank">caevear@gmail.com</a>
            <h1 class="Info">Instagram</h1>
            <a href="https://www.instagram.com/caevear/?hl=en" class="Redirect" target="_blank">@caevear</a>
        </div> -->
        <div class="InfoContainer">
            <a href="https://www.instagram.com/caevear" class="Redirect" target="_blank">
            <div class="icons8-instagram" ></div></a>
            <a href="https://www.tiktok.com/@caevear" class="Redirect" target="_blank">
                <div class="icons8-tiktok" ></div></a>
        </div>
    </div>
</template>

<style scoped>
.InfoContainer {
    /* display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 6rem; */
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap; 
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

.icons8-tiktok {
    display: inline-block;
    width: 32px;
    height: 32px;
    background: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHg9IjBweCIgeT0iMHB4IiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCI+CjxwYXRoIGQ9Ik0gNiAzIEMgNC4zNTUwMzAyIDMgMyA0LjM1NTAzMDIgMyA2IEwgMyAxOCBDIDMgMTkuNjQ0OTcgNC4zNTUwMzAyIDIxIDYgMjEgTCAxOCAyMSBDIDE5LjY0NDk3IDIxIDIxIDE5LjY0NDk3IDIxIDE4IEwgMjEgNiBDIDIxIDQuMzU1MDMwMiAxOS42NDQ5NyAzIDE4IDMgTCA2IDMgeiBNIDEyIDcgTCAxNCA3IEMgMTQgOC4wMDUgMTUuNDcxIDkgMTYgOSBMIDE2IDExIEMgMTUuMzk1IDExIDE0LjY2OCAxMC43MzQxNTYgMTQgMTAuMjg1MTU2IEwgMTQgMTQgQyAxNCAxNS42NTQgMTIuNjU0IDE3IDExIDE3IEMgOS4zNDYgMTcgOCAxNS42NTQgOCAxNCBDIDggMTIuMzQ2IDkuMzQ2IDExIDExIDExIEwgMTEgMTMgQyAxMC40NDggMTMgMTAgMTMuNDQ5IDEwIDE0IEMgMTAgMTQuNTUxIDEwLjQ0OCAxNSAxMSAxNSBDIDExLjU1MiAxNSAxMiAxNC41NTEgMTIgMTQgTCAxMiA3IHoiPjwvcGF0aD4KPC9zdmc+') 50% 50% no-repeat;
    background-size: 100%;
}

.icons8-instagram {
    display: inline-block;
    width: 32px;
    height: 32px;
    background: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHg9IjBweCIgeT0iMHB4IiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCI+CiAgICA8cGF0aCBkPSJNIDggMyBDIDUuMjQzIDMgMyA1LjI0MyAzIDggTCAzIDE2IEMgMyAxOC43NTcgNS4yNDMgMjEgOCAyMSBMIDE2IDIxIEMgMTguNzU3IDIxIDIxIDE4Ljc1NyAyMSAxNiBMIDIxIDggQyAyMSA1LjI0MyAxOC43NTcgMyAxNiAzIEwgOCAzIHogTSA4IDUgTCAxNiA1IEMgMTcuNjU0IDUgMTkgNi4zNDYgMTkgOCBMIDE5IDE2IEMgMTkgMTcuNjU0IDE3LjY1NCAxOSAxNiAxOSBMIDggMTkgQyA2LjM0NiAxOSA1IDE3LjY1NCA1IDE2IEwgNSA4IEMgNSA2LjM0NiA2LjM0NiA1IDggNSB6IE0gMTcgNiBBIDEgMSAwIDAgMCAxNiA3IEEgMSAxIDAgMCAwIDE3IDggQSAxIDEgMCAwIDAgMTggNyBBIDEgMSAwIDAgMCAxNyA2IHogTSAxMiA3IEMgOS4yNDMgNyA3IDkuMjQzIDcgMTIgQyA3IDE0Ljc1NyA5LjI0MyAxNyAxMiAxNyBDIDE0Ljc1NyAxNyAxNyAxNC43NTcgMTcgMTIgQyAxNyA5LjI0MyAxNC43NTcgNyAxMiA3IHogTSAxMiA5IEMgMTMuNjU0IDkgMTUgMTAuMzQ2IDE1IDEyIEMgMTUgMTMuNjU0IDEzLjY1NCAxNSAxMiAxNSBDIDEwLjM0NiAxNSA5IDEzLjY1NCA5IDEyIEMgOSAxMC4zNDYgMTAuMzQ2IDkgMTIgOSB6Ij48L3BhdGg+Cjwvc3ZnPg==') 50% 50% no-repeat;
    background-size: 100%;
}
</style>