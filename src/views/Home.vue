<template>
    <div class="home page-padding">
        <header></header>
        <footer></footer>
    </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import Header from '@/components/home/Header.vue';
import Footer from '@/components/home/Footer.vue';

@Component({
    components: {
        Header,
        Footer
    }
})
export default class Home extends Vue {

};
</script>

<style lang="scss">

</style>
