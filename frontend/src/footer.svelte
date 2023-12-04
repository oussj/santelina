<script>

    import { goto } from "$app/navigation"
    function handleClick() {
        goto('/Privacy');
    }
    </script>


<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<footer>
    <div class="imgback">
        <img class="sea" src="./images/mont.jpg" alt="">

    </div>
    
    <div class="bottom1-footer">
             <div><p class="bottom-text"> Copyright © 2023 | ############## |</p></div><div><p> <a href="#" on:click={handleClick}>Privacy Policy</a></p></div><div> <p>| Créé par M.Naksho</p></div>
        </div>
</footer>
<style>

    footer{
        width: 100%;
        display: block;
    }
    .imgback{
        width: 100%;
        height: 300px;
    }
    .sea{
        height: 300px;
        width: 100%;
    }
    
    .bottom1-footer{
        margin-top: auto;
        display: flex;
        justify-content: space-around;
        width: 100%;
        background-color: #90719D;
        color: white;
    }
    a{
        text-decoration: none;
        color: rgba(255, 255, 255, 0.584);
    }


@media screen and (min-width: 320px) and (max-width: 1600px){
    .bottom1-footer{
        width: 100%;
    }
    
}
@media screen and (min-width:320px) and (max-width:480px) {
    p{
        font-size: 11px;
    }
}
@media screen and (min-width:481px) and (max-width:768px) {
   
}
@media screen and (min-width:769px) and (max-width:1024px) {

    .bottom-text{
        font-size: 14px;
    }
}
@media screen and (min-width:1025px) and (max-width:1200px) {
    
    .bottom-text{
        font-size: 17px;
    }
}
    
</style>