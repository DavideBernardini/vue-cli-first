<template>
    <div class="jumbo">
        <div class="title">
            <Title/>
        </div>
        <p>
            Vue provides an official CLI for quickly scaffolding ambitious Single Page Applications. It provides batteries-included build setups for a modern frontend workflow. It takes only a few minutes to get up and running with hot-reload, lint-on-save, and production-ready builds.
        </p>
    </div>
</template>

<script>
import Title from '../components/Title.vue'

export default {
    name: 'Hero',
    components: {
        Title
    }
}
</script>

<style>
    .jumbo {
        background-image: url(https://www.vuemastery.com/images/courses/hero_compressed.jpg);
        background-size: cover;
        background-position: center;
        height: 600px;
        padding: 50px 80px;
    }
    .title {
        color: #7efcf8;
    }
    p {
        color: #37b9a1;
        width: 350px;
        font-size: 20px;
        margin-top: 30px;
    }
</style>