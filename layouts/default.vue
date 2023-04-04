<template>
    <header>
        <Header></Header>
    </header>
    <main>
        <slot></slot>
    </main>
    <footer>
        <Footer></Footer>
    </footer>
</template>
<script setup>
import Header from '~/components/Header.vue';
import Footer from '~/components/Footer.vue';
</script>
