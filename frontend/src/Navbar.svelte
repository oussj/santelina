<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css" integrity="sha512-MV7K8+y+gLIBoVD59lQIYicR65iaqukzvf/nwasF0nqhPay5w/9lJmVM2hMDcnK1OnMGCdVK+iQrJ7lzPJQd1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<!--
<script>
    import { page } from "$app/stores"
    const navs = [
    {
        title: "Accueil",
        href: "/",
    },
    {
        title: "Naturopath",
        href: "/Naturopath",
    },
    {
        title: "Blog",
        href: "/Blog",
    },
    {
        title: "Contacte",
        href: "/contact",
    },
    ];

    $: routeId = $page.route.id;

    
    
</script>

<nav>
    <div class="container">
        <div class="nav-toggle">
            <i class="fa-solid fa-bars" id="menu-icon"></i>
        </div>
        <ul class="navbar">
            {#each navs as {title, href } }
            <li>
            <a {href} class:active={routeId == href} {title}>{title}</a>
            </li>
            {/each}
        </ul>
    </div>
</nav>

<style>
    nav{
        padding: 0.5em;
        background-color: #8fab72;;
        color: white;
        height: 60px;
        display: flex;
    }

    .container {
        display: flex;
        align-items: center;
    }
    ul {
        display: flex;
        margin: 0;
        margin-left: auto;
        list-style: none;
        font-size: 1em;
    }
    li{
        margin-right: 100px;
        font-size: large;
    }

    a {
        text-decoration: none;
        color: rgba(255, 255, 255, 0.584);
        
     }
    .active {
        color: rgb(250, 247, 247);
    }
    .nav-toggle {
    display: none;
    cursor: pointer;
}


.navbar a{
    font-size: 1.1rem;
    font-weight: 500;
    padding: 5px 0;
    margin: 0px 30px;
    transition: all .50s ease;
}
.navbar a:hover{
    color:  var(--main-color);
}
.navbar a:active{
    color:  var(--main-color);
}
#menu-icon{
    font-size: 35px;
    color: var(--text-color);
    cursor: pointer;
    z-index: 10001;
    display: none;
}

@media (max-width: 1280px){
    .navbar a{
        padding: 5px 0;
        margin: 0px 20px;
    }
}
@media (max-width: 1090px){
    #menu-icon{
        display: block;
    }
    .navbar{
        position: absolute;
        top: 100%;
        right: 2%;
        width: 270px;
        height: 29vh;
        background: var(--main-color);
        
    }
    .nav-toggle {
        display: block;
    }
}
/* @media (max-width: 767px) {
    .nav-toggle {
        display: block;
    }
    
    ul {
        display: none;
    }
} */
</style>
 -->

<script>
    let showMenu = false;

    function toggleMenu() {
    showMenu = !showMenu;
    }
</script>
<main>
<nav>
    
    <div class="menu-icon" on:click={toggleMenu}>
        <i class="fa-solid fa-bars"></i>
    </div>
    <ul class="nav-links" class:show={showMenu}>
        <li><a href="/Home"><p>Accueil</p></a></li>
        <li><a href="/Naturopath"><p>Naturopathie</p></a></li>
        <li><a href="/Blog"><p>Blog</p> </a></li>
        <li><a href="/Maladies"><p>Articles</p> </a></li>
        <li><a href="/contact"><p>Contact</p> </a></li>
        
    </ul>
</nav>
</main>
<style>
    main{
        width: 100%;
    }
    nav {
        width: 100%;
        background-color: #90719D;
        display: flex;
        justify-content: space-around;
        
    }
    .menu-icon {
        display: none;
        cursor: pointer;
    }
    .nav-links {
        display: flex;
        list-style: none;
        margin: auto 0;
        padding: 0;
        color: rgb(255, 255, 255);
    }
    .nav-links:checked{
        color: aliceblue;
    }
    ul{
        color: rgb(255, 255, 255);
    }

    .nav-links li {
        margin: 0 4rem;
        border-radius: 50%;
    }

    .nav-links a {
        text-decoration: none;
        color: #ffffff;
        font-size: 1.2rem;
    }
@media screen and (min-width: 1001px) and (max-width: 1600px){
    nav{
        width: 100%;
    }
}
    @media (max-width: 800px) {
        .menu-icon {
            
        display: block;
        
}



    .nav-links {
        display: none;
        align-items: center;
        text-align: center;
    }
    .nav-links.show {
        display: block;
        position: absolute;
        background: #78b575;
        border: 1px solid #ddd;
        border-radius: 5px;
        width: 100%;
        height: 300px;
    }
    p{
        text-align: center;
    }
    }
    @media screen and (min-width: 360px) and (max-width: 1000px) {
       
        .menu-icon {
            
            display: block;
            
    }
        .nav-links.show {
        display: block;
        position: absolute;
        top: 45%;
        background: #90719D;
        border: 1px solid #ddd;
        border-radius: 5px;
        width: 100%;
        height: 250px;
        
    }
        ul li {
            width: 80%;
            font-size: 30px;
            
        }
        .nav-links {
        display: none;
        align-items: center;
        text-align: center;
    }
        

    }
    @media screen and (min-width: 360px){
        nav{
            width: 100%;
        }

    }
</style>
