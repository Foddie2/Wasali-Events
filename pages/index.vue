<template>
<Navbar/>
<Hero/>
</template>

<script>
import Navbar from '~/components/Navbar.vue';
import Hero from '~/components/Hero.vue';
export default {
    name: "IndexPage",
    components: { Navbar, Hero }
}
</script>
