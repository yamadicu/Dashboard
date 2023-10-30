<script>
export default{
    name: "SideComp"
}
</script>

<template>
    <aside>

    
        <h6>- Dashbool -</h6>

        <div class="d-flex">

            <img src="/img/man.png" alt="">

            <div class="d-flex flex-column m-auto mx-3">
                <span>Welcome</span>
                <span class="fs-6 fw-bold">Mario Rossi</span>
            </div>

        </div>

        <div>

            <span class="text-uppercase">
                general
            </span>

            <hr>

            <ul>
                <li>
                    <i class="fa-solid fa-house"></i>
                    Home
                    <i class="fa-solid fa-chevron-down"></i>

                    <ul>
                        <li>
                            Dashboard
                        </li>
                        <li>
                            Dashboard 1
                        </li>
                        <li>
                            Dashboard 2
                        </li>
                    </ul>

                </li>

                <li>
                    <i class="fa-solid fa-map"></i>
                    Maps
                    <i class="fa-solid fa-chevron-up"></i>
                </li>

                <li>
                    <i class="fa-solid fa-gear"></i>
                    Config
                    <i class="fa-solid fa-chevron-up"></i>
                </li>

                <li>
                    <i class="fa-solid fa-envelope"></i>
                    Contacts
                    <i class="fa-solid fa-chevron-up"></i>
                </li>
            </ul>

        </div>

    </aside>
</template>

<style lang="scss">

aside{
    width: 10vw;
    height: 100vh;
    padding: 0 5px;
    padding-top: 10px;
    background-color: rgb(42 64 84);
    color: white;

    img{
        height: 50px;
        width: 50px;
        margin: 10px 0;
        border-radius: 50px;
        border: 2px solid white;
    }

    hr{
        margin: 5px;
        color: white;
    }

    ul{
        margin-left: -15px;
        li{
            list-style-type: none;
        }
    }
}
</style>