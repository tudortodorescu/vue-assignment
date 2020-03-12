<template>
    <div class="container">
        <app-header></app-header>
        <hr>
        <app-content></app-content>
        <hr>
        <app-footer></app-footer>
    </div>
</template>

<script>
    import Header from './components/Header.vue'
    import Content from './components/content/Content.vue'
    import Footer from './components/Footer.vue'

    export default {
        components: {
            'app-header': Header,
            'app-content': Content,
            'app-footer': Footer
        }
    }
</script>