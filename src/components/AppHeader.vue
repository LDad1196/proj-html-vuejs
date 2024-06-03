<script>
    import store from '../data/store.js';

    export default {
        data() {
            return {
                store,
                links: [
                {
                    text: "HOME",
                    url: "#HOME",
                },
                {
                    text: "PAGES",
                    url: "#PAGES",
                },
                {
                    text: "TOURNAMENT",
                    url: "#TOURNAMENT",
                },
                {
                    text: "SHOP",
                    url: "#SHOP",
                },
                {
                    text: "BLOG",
                    url: "#BLOG",
                },
                {
                    text: "CONTACT",
                    url: "#CONTACT",
                }
            ],
            }
        }
    }
</script>

<template>
    <header class="my-bg">
        <div class="container">
            <div class="flex row align-items-center py-3 px-0 w-100">
                <figure class="col-2 mx-0 px-0">
                    <img src="../assets/menulogo.png" class="img-fluid" alt="">
                </figure>
                <nav class="col-8 p-0">
                    <ul class=" flex row mx-0 justify-content-center">
                        <li v-for="link in links" class="col-2">
                            <a :href="link.url" class="text-decoration-none hover">
                                <b>{{link.text}}</b>
                            </a>
                        </li>
                    </ul>
                </nav>
                <div class="col-2 flex row justify-content-center align-items-center">
                    <div class="col-6">
                        <a href="search"><i class="fa-solid fa-magnifying-glass"></i></a>
                    </div>
                    <div class="col-6">
                        <a href="bag"><i class="fa-solid fa-bag-shopping"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<style scoped>
    .my-bg {
        height: 80vh;
        background-image: url(../assets/banner1.png);
        background-repeat: no-repeat;
        background-size: cover;
        background-position: top;
        color: white;
    }
    
    a {
        text-decoration: none;
        color: white;
    }
    
    li {
        list-style-type: none;
    }
    
</style>
