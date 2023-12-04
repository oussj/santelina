
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Work+Sans:ital,wght@1,300&display=swap" rel="stylesheet">
</head>
<div class="head-page">
    <br>
</div>
<div class="container">
    <div class="text-column">
        <h2 class="container1-h2">L'arthrose</h2>
        
        <div class="icon-w">
            <p class="container-span" >L'arthrose est d'un côté une maladie professionnelle due à l'usage répété de l'articulation. De l'autre côté, c'est une maladie dégénérative, exactement comme le diabète ou la maladie d'Alzheimer.
                Ces maladies, dites « dégénératives », font partie des affections pour lesquelles la prévention est essentielle pour stopper leur progression et leur aggravation.
                L'arthrose d’une cause physique , n'est pas une maladie générale, mais plutôt une atteinte locale de l'articulation fortement sollicitée.
                En revanche , le nombre de cas d'arthrose généralisé a doublé en 50 ans, principalement à cause du changement de mode de vie : sédentarité, positions assises prolongées, mais surtout une alimentation pro-inflammatoire (trop de sucre et de fructose, trop de produits ultra-transformés, de plats préparés, trop d'acides gras saturés ou trans, trop de viande, notamment la viande rouge).
                Tous ces facteurs favorisent l'inflammation de bas grade et les maladies dégénératives du cartilage, telles que l'arthrose. D’où vient l, 'intérêt du régime méditerranéen, qui comporte peu de viande et de poisson, davantage de légumes, de fruits et de bonnes huiles. Ce régime est validé par de nombreuses études. Il est considéré comme le meilleur  pour éviter les maladies dégénératives."</p>
</div>
<p> <em> L.Jaber 15, 08, 2023  </em></p>
<br>
</div>
    <div class="image-column">
                <img class="sea" src="./images/1668677929784lakvr709.jpg" alt="">

    </div>
    </div>
    
    <style>
        .container {
    display: flex;
    flex-direction: row;
    width: 100%;
    margin: 0 auto;
}
.container1-h2{
    font-weight: 400;
}
.text-column {
    width: 85%;
    
}
p{
    color: rgb(74, 15, 102);
}
h2{
    font-weight: 300;
    color: rgb(74, 15, 102);
}
.image-column {
    width: 75%;
    order: -1;
}
img {
    width: 100%;
    height: auto;
}
.container-span{
    font-weight: 400;
    line-height: 2rem;
}
.head-page{
    display: flex;
    margin: 0 auto;
    width: 100%;
}
.h1-head{
    font-weight: 400;
}
@media screen and (min-width: 801px) and (max-width: 1500px) {
    .container {
        display: block;
        width: 100%;
        font-size:14px;
        text-align: center;
    }
    h2{
        padding-left: 8rem;
    }
    p{
        padding-left: 120px;
    }
}
@media screen and (min-width: 401px) and (max-width: 800px){
    .container {
        display: block;
        width: 100%;
        font-size:15px;
    }
    p{
        text-align: center;
        margin: 0 auto;
        padding-left: 60px;
    }
    
}

@media (max-width: 800px){
    .image-column {
        display: none;
    }
}
</style>