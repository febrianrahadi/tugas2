<template>
    <div id="app">
        <headerDriver />
        <Nuxt />
        <footerDriver />
    </div>
</template>

<script>

import headerDriver from "@/components/headerDriver.vue"
import footerDriver from "@/components/footerDriver.vue"
export default {

components: {
headerDriver,
footerDriver
}
}
</script>
<style>
</style>