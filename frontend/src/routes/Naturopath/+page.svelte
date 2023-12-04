<script>

import { goto } from "$app/navigation"
function handleClick() {
    goto('/contact');
}
</script>
<head>
        <meta name="viewport" content="width=device-width, initial-scale=1" /><link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Work+Sans:ital,wght@1,300&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css" integrity="sha512-MV7K8+y+gLIBoVD59lQIYicR65iaqukzvf/nwasF0nqhPay5w/9lJmVM2hMDcnK1OnMGCdVK+iQrJ7lzPJQd1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
                                                    <!-- CONTAINER -->
<div class="container">
    <div class="text-column">
        <h1>les bénéfices de la suivi naturopathique</h1>
        <hr class="hr-natur">
        <br><br>
        <div class="icon-w">
            <p class="container-span" >Approche globale : la naturopathie prend en considération la personne dans sa globalité, en
                cherchant à identifier les causes sous-jacentes des problèmes de santé plutôt que de simplement
                traiter les symptômes. Cela permet de favoriser une meilleure compréhension de son propre corps et
                de ses besoins.
                
                Prévention : elle insiste sur la prévention des maladies en adoptant un mode de vie sain et équilibré.
                Cela encourage des changements dans l’alimentation, l’exercice, la gestion du stress et d’autres
                aspects de la vie pour promouvoir une santé optimale à long terme.
                
                Renforcement du système immunitaire : En optimisant l&#39;alimentation et en utilisant des
                suppléments nutritionnels appropriés , ça peut contribuer à renforcer le système immunitaire et
                améliorer la résistance aux maladies.
                
                Gestion du stress : Les séances de naturopathie peuvent inclure des techniques de relaxation et de
                gestion du stress, ce qui peut aider à réduire l&#39;anxiété et à améliorer la qualité du sommeil.
                
                Amélioration de la digestion : apporter des recommandations pour améliorer la digestion et
                l&#39;absorption des nutriments, ce qui peut avoir un impact positif sur l&#39;énergie et la santé générale.
                
                Soulagement des symptômes : En ciblant les causes profondes des problèmes de santé, la
                naturopathie peut contribuer à soulager les symptômes liés à certaines conditions chroniques.
                
                Bien-être émotionnel : En travaillant sur l&#39;équilibre global de la personne, la naturopathie peut aider
                à améliorer l&#39;humeur, la clarté mentale et la vitalité émotionnelle.
                
                Accompagnement personnalisé : Les séances sont adaptées aux besoins spécifiques de chaque
                individu, ce qui offre un accompagnement personnalisé dans son parcours vers une meilleure santé.</p>
</div><br>
</div>
    <div class="image-column">
    </div>
    </div>
    
                                                                <!-- button-Container  -->
        <div class="button-Container">
            <div class="btn-text">
                <h1 class="btn-h1">Réservez des maintenant</h1>
            </div>
            <div>
                <button class="book-btnb" on:click={handleClick}>Réservez</button>
            </div>
        </div>
<br><br><br>
    <style>
        
                                                        /* CONTAINER */
        .container {
    display: flex;
    flex-direction: row;
    width: 100%;
    margin: 0 auto;
}

.text-column {
    width: 75%;
    padding: 20px;
}
.image-column {
    width: 75%;
    padding: 20px;
    order: -1;
}

.hr-natur{
    width: 150px;
    margin-left: 0;
}
h1{
    font-family: 'Poppins', sans-serif;
    font-weight: 300;
    color:rgb(74, 15, 102);
    line-height: 1.2;
}
p{
    color:rgb(74, 15, 102);
    font-size: 2rem;
    font: 1em sans-serif;
    line-height: 1.9;
}
@media screen and (min-width: 320px) and (max-width: 480px){
    .container {
        flex-direction: column;
        width: 100%;
    }
}
@media screen and (min-width: 481px) and (max-width: 800px){
    .container {
        flex-direction: column;
        width: 100%;
    }
}
                                                    /* CONTAINER SPAN */
.container-span{
    font-size: 1em;

}
                                                    /* CONTAINER 2 */

@media screen and (max-width: 400px){
    p{
        font-size: 15px;
    }
    
    
}
@media screen and (min-width: 320px) and (max-width: 800px){
    p{
        font-size: 15px;
    }   
}

                                /* button-container */
.button-Container{
    background-color: #90719D;
    width: 40%;
    display: flex;
    margin: 0 auto;
    padding: 20px;
    height: 70px;
    border-radius: 8px;
}
button{
    position:relative; left:68px; top:40px;
    border: none;
}
.book-btnb{
    border-radius: 22px;
    background-color: rgb(74, 15, 102);
    width: 100px;
    height: 40px;
    border-color: #8fab72;
    color: white;
    font-size: medium;
    
}

.btn-h1{
    color: white;
}
@keyframes slidInTop {
    from{
        transform: translateY(-300PX);
    }
    to{
        transform: translateY(0);
    }
}
.button-Container{
    animation-name: slidInTop;
    animation-duration: 1s;
    animation-direction: alternate;
}

@media screen and (min-width: 320px) and (max-width: 1000px){
    .button-Container{
        width: 80%;
        display: block;
        height: 150px;
        font-size: 10px;
        text-align: center;
        
    }
    .book-btnb{
        position: relative; left: 0px; top: 20px;
    }
}
@media screen and (min-width: 1001px) and (max-width: 1200px){
    
    .button-Container{
        width: 80%;
        display: block;
        height: 200px;
    }
    
}
@media screen and (min-width: 1201px) and (max-width: 1500px){
    .button-Container{
        font-size: 10px;
        width: 32%;
    }
    
    .book-btnb{
        position: relative; left: 70px; top: 10px; 
        width: 9em;
    }
}
</style>