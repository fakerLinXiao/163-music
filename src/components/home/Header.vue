<template>
    <div class="header-wrapper">
        <div class="menu-icon">menu</div>
        <div class="top-tab">
            <div>我的</div>
            <div>发现</div>
            <div>云村</div>
            <div>视频</div>
        </div>
        <div class="search-icon">menu</div>
    </div>
</template>

<script lang="ts">
import { Vue } from "vue-property-decorator";

export default class Header extends Vue {
    
}
</script>

<style lang="scss">
    .header-wrapper {
        display: flex;

        .top-tab {
            flex: 1 0 auto;
            display: flex;
        }
    }
</style>
