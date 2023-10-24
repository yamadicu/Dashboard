<script>
export default{
    name: "SideComp"
}
</script>

<template>
    <section>

    
        <h6>- Dashbool -</h6>

        <div>

            <img src="/img/man.jpg" alt="">

            <div>
                <span>Welcome</span>
                <span>Mario Rossi</span>
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

    </section>
</template>

<style lang="scss">

section{
    width: fit-content;
    height: 100vh;
    padding: 0 10px;
    padding-top: 10px;
    background-color: rgb(42 64 84);
    color: white;

    img{
        height: 100px;
        width: 100px;
        border-radius: 50px;
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