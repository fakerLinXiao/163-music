<template>
    <div class="home page-padding">
        <home-header />
        <!-- <router-view></router-view> -->
        <footer></footer>
    </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HomeHeader from '@/components/home/Header.vue';
import Footer from '@/components/home/Footer.vue';

@Component({
    components: {
        HomeHeader,
        Footer
    }
})
export default class Home extends Vue {

};
</script>

<style lang="scss">

</style>
