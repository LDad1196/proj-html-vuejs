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
                    subLinks:[
                        "HOME ONE",
                        "HOME TWO",
                        "HOME THREE",
                        "HOME FOUR"
                    ]
                },
                {
                    text: "PAGES",
                    url: "#PAGES",
                    subLinks: [
                        "ABOUT US",
                        "MATCHES",
                        "TEAM",
                        "SQUAD",
                        "SQUAD DETAILS",
                        "COMING SOON",
                        "404"                    
                    ]
                },
                {
                    text: "TOURNAMENT",
                    url: "#TOURNAMENT",
                },
                {
                    text: "SHOP",
                    url: "#SHOP",
                    subLinks:[
                        "SHOP PAGE",
                        "SHOP DETAILS",
                        "CART PAGE"                        
                    ]
                },
                {
                    text: "BLOG",
                    url: "#BLOG",
                    subLinks:[
                        "BLOG PAGE",
                        "BLOG SINGLE"                        
                    ]
                },
                {
                    text: "CONTACT",
                    url: "#CONTACT",
                }
            ],

            socials:[
                {
                    social: "Facebook",
                    urlSocial: "../assets/image(4).svg"
                },
                {
                    social: "Twitter",
                    urlSocial: "../assets/image(5).svg"
                },
                {
                    social: "Linkedin",
                    urlSocial: "../assets/image(6).svg"
                },
                {
                    social: "Instagram",
                    urlSocial: "../assets/image(7).svg"
                },
            ],
            }
        }
    }
</script>

<template>
    <header class="my-bg">
        <div class="container">
            <!-- Sezione Header -->
            <div class="flex row align-items-center py-3 px-0 w-100">
                
                <!-- Logo Section -->
                <figure class="col-2 mx-0 px-0">
                    <img src="../assets/menulogo.png" class="img-fluid" alt="">
                </figure>
                
                <!-- Nav section -->
                <nav class="col-9 p-0">
                    <div class=" flex row m-0 p-0 px-2 w-100 justify-content-center">
                        <div class="dropdown col-1">
                            <button class="btn dropdown-toggle text-light border-none" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                                HOME
                            </button>
                            <ul class="dropdown-menu">
                                <li><button class="dropdown-item" type="button">Home One</button></li>
                                <li><button class="dropdown-item" type="button">Home Two</button></li>
                                <li><button class="dropdown-item" type="button">Home Three</button></li>
                                <li><button class="dropdown-item" type="button">Home Four</button></li>
                            </ul>
                        </div>
                        <div class="dropdown col-1">
                            <button class="btn dropdown-toggle text-light border-none" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                                PAGES
                            </button>
                            <ul class="dropdown-menu">
                                    <li><button class="dropdown-item" type="button">About us</button></li>
                                    <li><button class="dropdown-item" type="button">Matches</button></li>
                                    <li><button class="dropdown-item" type="button">Team</button></li>
                                    <li><button class="dropdown-item" type="button">Squad</button></li>
                                    <li><button class="dropdown-item" type="button">Squad Details</button></li>
                                    <li><button class="dropdown-item" type="button">404</button></li>
                                </ul>
                        </div>
                        <div class="col-2">
                            <button class="btn  text-light border-none" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                                TOURNAMENT
                            </button>
                        </div>
                        <div class="dropdown col-1">
                            <button class="btn dropdown-toggle text-light border-none" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                                SHOP
                            </button>
                            <ul class="dropdown-menu">
                                    <li><button class="dropdown-item" type="button">Shop Page</button></li>
                                    <li><button class="dropdown-item" type="button">Shop Details</button></li>
                                    <li><button class="dropdown-item" type="button">Cart Page</button></li>
                                </ul>
                        </div>
                        <div class="dropdown col-1">
                            <button class="btn dropdown-toggle text-light border-none" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                                BLOG
                            </button>
                            <ul class="dropdown-menu">
                                <li><button class="dropdown-item" type="button">Blog Page</button></li>
                                <li><button class="dropdown-item" type="button">Blog Single</button></li>
                            </ul>        
                        </div>
                        <div class="col-1">
                            <button class="btn text-light border-none" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                            CONTACT
                            </button>
                        </div>     
                    </div>  
                </nav>
                
                <!-- Sezione Shop -->
                <div class="col-1 flex row justify-content-between m-0 p-0">
                    <div class="col-6 bg-light my-size shop-zone">
                        <a href="search" class="violet-c "><i class="fa-solid fa-magnifying-glass"></i></a>
                    </div>
                    <div class="col-6 bg-light my-size shop-zone">
                        <a href="bag" class="violet-c"><i class="fa-solid fa-bag-shopping"></i></a>
                    </div>
                </div>
            </div>

            <div class="text-center myp ">
                <h6>WELCOME TO RAXG</h6>
                <h1 class="my-3">ARE YOU READY FOR YOUR NEXT CHALLENGE?</h1>
                <ul class="flex row align-items-center justify-content-center py-4">
                    <li class="col-2"><button type="button" class="btn btn-green">Read More <i class="fa-solid fa-arrow-right"></i></button></li>
                    <li class="col-2"><button type="button" class="btn btn-green"><i class="fa-solid fa-circle-play"></i></button></li>
                </ul>
            </div>

            <div>
                <ul class="banner-social">
                    <li class="my-2">
                        <a href="#"><i class="fa-brands fa-facebook"></i></a>
                    </li>
                    <li class="my-2">
                        <a href="#"><i class="fa-brands fa-twitter"></i></a>
                    </li>
                    <li class="my-2">
                        <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                    </li>
                    <li class="my-2">
                        <a href="#"><i class="fa-brands fa-instagram"></i></a>
                    </li>
                </ul>
            </div>
        </div>
    </header>
</template>

<style scoped>
    .my-bg {
        height: 100vh;
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

    .hover:hover{
        color: #00AC4D;
    }

    li:nth-child(3) {
        width: 16.66666667%;
    }
    
    .shop-zone {
        width: 45px;
        height: 45px;
        border-radius: 50%;
        line-height: 45px;
    }

    h1 {
        font-size: 5rem;
    }

    h6 {
        color: #00AC4D;
    }

    .myp {
        padding-top: 20rem;
    }

    .violet-c {
        color: #333287;
    }

    

    .my-size {
        width: 40px;
        height: 40px;
    }

    .btn-green {
        background-color: #00AC4D;
        color: #333287;
        padding: 20px;
    }

    .banner-social {
        position: absolute;
        top: 45%;
        left: 10%;
        transform: translate(-50%, -50%);
    }

    .banner-social > li {
        width: 45px;
        height: 45px;
        border-radius: 50%;
        line-height: 45px;
        background-color: #202046;
        text-align: center;
    }
    
    .banner-social > li:hover {
        background-color: #00AC4D;
    }

    .dropdown {
        position: relative;
        display: inline-block;
      }
      
      .dropdown-content {
        display: none;
        position: absolute;
        background-color: #f1f1f1;
        min-width: 160px;
        box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
        z-index: 1;
      }
      
      .dropdown-content a {
        color: black;
        padding: 12px 16px;
        text-decoration: none;
        display: block;
      }
      
      .dropdown-content a:hover {
        background-color: #ddd;
      }
      
      .dropdown:hover .dropdown-content {
        display: block;
      }
      
      .dropdown:hover .dropbtn {
        background-color: #4d1c33;
      }
</style>
