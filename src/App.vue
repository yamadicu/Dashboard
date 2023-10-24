<script>
import SideComp from './components/SideComp.vue';
export default{
    name: "app", 
    components:{
        SideComp
    }
}
</script>

<template>
    <SideComp></SideComp>
</template>

<style lang="scss">
@use './style/main.scss';
</style>
