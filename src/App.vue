<template>
    <img alt="logo" src="https://cdn.nakatai.ga/img/nakataimc.webp" />
    <ToolIntro msg="Nakatai's Tool List" />
</template>

<script>
import ToolIntro from "./components/ToolIntro.vue";

export default {
    name: "App",
    components: {
        ToolIntro
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
