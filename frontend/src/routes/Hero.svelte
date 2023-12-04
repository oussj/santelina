<script>

</script>


<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<header>
    
    
    <div class="hero">

        <div class="logo">
        <span>
            <a href="https://www.facebook.com/profile.php?id=100089682795278"><i class="fa-brands fa-facebook fa-2xl"></i></a>
            <a href="https://www.google.com/search?q=sant%C3%A9+lina+saint+quentin&rlz=1C1ONGR_frFR1046FR1046&oq=sant%C3%A9+lina+saint+quentin&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIHCAEQIRigATIHCAIQIRigAdIBCTY0OTk0ajBqN6gCALACAA&sourceid=chrome&ie=UTF-8"><svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="41" height="40" fill="none" viewBox="0 0 21 20">
                <path stroke="currentColor" strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M3.308 9a2.257 2.257 0 0 0 2.25-2.264 2.25 2.25 0 0 0 4.5 0 2.25 2.25 0 0 0 4.5 0 2.25 2.25 0 1 0 4.5 0C19.058 5.471 16.956 1 16.956 1H3.045S1.058 5.654 1.058 6.736A2.373 2.373 0 0 0 3.308 9Zm0 0a2.243 2.243 0 0 0 1.866-1h.767a2.242 2.242 0 0 0 3.733 0h.767a2.242 2.242 0 0 0 3.733 0h.767a2.247 2.247 0 0 0 1.867 1A2.22 2.22 0 0 0 18 8.649V19H9v-7H5v7H2V8.524c.37.301.83.469 1.308.476ZM12 12h3v3h-3v-3Z"/>
              </svg></a>
        </span>
        

    </div>
        <div class="text"><a href="https://maps.app.goo.gl/zMRzDsWHQLoe7ifm7">5 Rue Paul Doumer - 02100 ST-Quentin</a>
        <p class="tow">0745123085</p></div>
        
        <div class="container">
            <img src="/images/filogo.jpg" alt="logo">
            <!-- <button onclick="contact/+page.svelte" class="headBtn">Reservez des maintenant</button> -->
        </div>
    </div>
    </header>
    <style>

        
        .hero{
        height: 175px;
        margin: 0;

        background-repeat: no-repeat;   
        color: rgb(230, 190, 203);
        }
        img{
            position: relative;
            right: 90%;
            bottom: 20%;
            width: 200px;
        }
        .hero{
            height: 175px;
            margin: 0;
            background-image: url('/images/.jpg');
            background-repeat: no-repeat;   
            display: flex;
            color: #fffbfa;
        }
       
        /* .headBtn {
            border-radius: 22px;
            background-color: #8fab72;
            width: 260px;
            height: 40px;
            border-color: #8fab72;
            color: white;
            font-size: medium;
            position:relative; left:950px; top:120px;
            border: none;
        } */

@media screen and (max-width:1499px) {
    .hero {
        width: 100%;
    }
}

.text{
    display: block;
    color: black;
}
.text a{
    display: block;
    color: black;
    text-decoration: none;
}

.text .tow{

    color: black;
    padding-left: 75px;
}
 
.logo{
    width: 100px;
    display: flex;
    position: relative;
    left: 90%;
    top: 15%;
}

.w-6{
    position: relative;
    top: 8%;
    left: 20%;
}

@media screen and (min-width: 360px) and (max-width: 1000px) {
        .hero {
            display: flex;
            width: 100%;
        }
    }

    @media screen and (max-width: 600px){
        .hero{
            display: none;
        }
    }
 </style>