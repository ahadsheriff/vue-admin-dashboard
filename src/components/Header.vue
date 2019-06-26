<template>
    <div id="nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
    </div>
</template>

<script>
    import Header from "@/components/Header.vue"
    export default {
        name: "home",
        components: {
            HelloWorld,
            Header
        }
    }
</script>

<style lang="scss" scoped>

</style>