<script>
export default{
    name: "TopComp"
}
</script>

<template>
    <section>

        <nav class="navbar navbar-expand-lg bg-body-tertiary">
            <div class="container-fluid">
                <i class="fa-solid fa-bars"></i>
    
                <div class="d-flex align-items-center">
                    <i class="fa-solid fa-envelope"></i>
                    <img class="mx-4" src="/img/man.png" alt="">
                    <span>Mario Rossi</span>
                    <i class="fa-solid fa-chevron-down"></i>
                </div>
            </div>
        </nav>
    </section>
</template>

<style lang="scss">
section{
    width: 100vw;
    img{
        width: 50px
    };
}
</style>