<template>
    <div class="home-box">
        <!-- 头部组件 -->
        <Header></Header>
        <!-- 搜索组件 -->

        <!-- 列表 -->
    </div>
</template>
 

<script setup>
import { ref } from 'vue';
import Header from './components/header.vue';
</script>


<style lang="scss" scoped>
.home-box{
    width: 100%;
    min-height: 100vh;
    background: wheat;
    display: flex;
    flex-direction: column;
}
</style>