<template>
    <Home />
    <Frame />
    <About />
</template>

<script>
    import Frame from "@/components/Frame/Frame.vue";
    import Home from "@/components/Home/Home.vue";
    import About from "@/components/About/About.vue";
    export default {
        components: {
            Frame,
            Home,
            About,
        },
    };
</script>

<style></style>
