<template>
    <img alt="logo" src="https://cdn.nakatai.ga/img/nakataimc.webp" />
    <HelloWorld msg="Nakatai Tools List" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
    name: "App",
    components: {
        HelloWorld,
    },
};
</script>

<style>
@import url("//fonts.googleapis.com/css2?family=Montserrat&display=swap");
@import url("//fonts.googleapis.com/css2?family=Noto+Sans+JP&display=swap");
@import url("//fonts.googleapis.com/css2?family=JetBrains+Mono&display=swap");

#app {
    font-family: "Montserrat", "Noto Sans JP", sans-serif;
    font-weight: 400;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
