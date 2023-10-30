<script>
import SideComp from './components/SideComp.vue'
import TopComp from './components/TopComp.vue'
import MainComp from './components/MainComp.vue';
export default{
    name: "app", 
    components:{
        SideComp,
        TopComp,
        MainComp
    }
}
</script>

<template>
    <section class="d-flex">

        <SideComp></SideComp>
        <TopComp></TopComp>
        <MainComp></MainComp>
        
    </section>
</template>

<style lang="scss">
@use './style/main.scss';
</style>
