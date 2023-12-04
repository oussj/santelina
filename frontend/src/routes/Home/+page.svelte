
<script>
    export let data;


import { goto } from "$app/navigation"
function handleClick() {
goto('/Home')
}

</script>
<head>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Work+Sans:ital,wght@1,300&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css" integrity="sha512-MV7K8+y+gLIBoVD59lQIYicR65iaqukzvf/nwasF0nqhPay5w/9lJmVM2hMDcnK1OnMGCdVK+iQrJ7lzPJQd1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
<div class="container">
<div class="text-column">
<h2>Lina Jaber (Santélina)</h2>
<hr>
<p>Je suis naturopathe holistique diplômée en médecine générale de la faculté de médecine à Damas ,  j'ai également obtenu des  diplômes  en Naturothérapie  à  l'université Bobigny 13  et l'école de naturopathie  " KOREVA"

En tant que naturopathe, j’accompagne mes clients sur le chemin de l’auto-guérison en leur fournissant les outils nécessaires pour surmonter leurs maladies chroniques.
<br><br>
Est-ce que vous:</p>
<div class="icon-w">
<span class="fa-solid fa-chevron-right" style="font-size: 36px; margin-right: 10px;"></span>
<span>Vous souffrez d'une maladie chronique ?</span>
</div>
<div>
<br>
<span class="fa-solid fa-chevron-right" style="font-size: 36px; margin-right: 10px;"></span>
<span>Vous soufrez d'une fatigue inexpliquée </span>
</div>
<br>
<div>
<span class="fa-solid fa-chevron-right" style="font-size: 36px; margin-right: 10px;"></span>
<span>Vous avez toujours des symptômes malgré le traitement médicamenteux?</span>
</div>
<br>
</div>
<div class="image-column">
<img src="https://www.emmamoorbynd.com/wp-content/uploads/bb-plugin/cache/ezgif.com-gif-maker4-1536x1304-square.jpg" alt="image">
</div>
</div>

<div class="header-column-support">
<!-- (No content, remove if not used) -->
</div>

<div class="container1">
<div class="left-column">
<div class="left-head-support">
<div class="left-icon-text">
    <h3 class="left-right-column-text">Déroulement d'une séance:</h3>
    <hr class="left-hr-head">
</div>
</div>
<div class="icon-left">
<span> 1. 	Entretien initial : recueillement des informations détaillées sur l'état de  votre santé , vos antécédents médicaux, vos habitudes de vie, votre  alimentation, votre niveau de stress, etc. <br><br>
    2.	Bilan de vitalité : pour évaluer l' état général et identifier d’éventuels déséquilibres dans votre corps. <br><br>
    3.	Analyse des besoins . <br><br>
    4.	Plan d’action personnalisé . <br><br>
    5.	Approche globale de la personne dans sa globalité, en cherchant à identifier et traiter les causes profondes des déséquilibres plutôt que de se focaliser uniquement sur les symptômes. <br> </span>
</div>
</div>
<div class="right-column">
<div class="right-head-support">
<div class="right-icon-text">
    <h3 class="left-right-column-text"></h3>
</div>
</div>
<div class="icon-right">
<div>
    <span>Allérgie</span></div>
<div>
    <span>Anxiété</span></div>
<div>
    <span>Problèmes de transite</span></div>
<div>
    <span>Perte de poids</span> <br></div>
<div>
    <span>Équilibre acido-basique</span></div>
<div>
    <span>Stress et dépression</span></div>
<div>
    <span>Problèmes de thyroïde</span></div>
</div>
</div>
</div>

<div class="container4">
<!-- <center>
<div class="anpimg">
<img class="img1" src="https://syndicat-naturopathie.fr/wp-content/uploads/2021/06/logo_officiel-SPN-.jpg" alt="anpimg">
</div>
<div class="gncimg">
<img class="img2" src="./images/kalae-rs-icon.7574d8e0.png" alt="gncimg">
</div>
<div class="ecoimg">
<img class="img3" src="http://idenat.fr/wp-content/uploads/2015/01/logo-IDENAT-N%C2%B02-et-17-redim-2.png" alt="ecoimg">
</div>

</center>
-->
</div>    
<h1>{data.data}</h1>

</body>


<style>
                                /* Welcome to Lina  Naturopathy */
/* Welcome to Lina Naturopathy */

.container {
flex-direction: row;
width: 100%;
display: flex;
}

center {
display: flex;
}





h3{
color: rgb(74, 15, 102);
}

h2{
font-weight: 50;
color:rgb(74, 15, 102);

}

.text-column {
width: 50%;
order: -1;
}

.image-column {
width: 50%;
padding: 20px;
}

img {
width: 100%;
height: auto;
}

@media (max-width: 480px) {
img {
width: 100%;
}
}




span{
color:rgb(74, 15, 102);

}


p {
color:rgb(74, 15, 102);
font-size: 2rem;
font: 1em sans-serif;
line-height: 1.9;
}

.fa-solid {
font-size: 36px;
margin-right: 10px;
vertical-align: middle;
color: rgb(74, 15, 102);
}

h3 {
font-family: 'Poppins', sans-serif;
font-weight: 300;
color:rgb(74, 15, 102);
line-height: 1.2;
}

@media screen and (min-width: 320px) and (max-width: 1000px) {
.container {
display: block;
width: 100%;
}
.image-column{
display: none;
}
}

/* I support clients with: & CONTAINER1 */


@media screen and (min-width: 320px) {
.header-column-support {
width: 100%;
}
}

@media screen and (max-width: 1020px) {
.header-column-support {
width: 100%;
}
}

.container1 {
display: flex;
width: 100%;
background-color: #ffffff;
margin: 0 auto;
}


.text-column{
padding-left: 30px;
}

.left-column,
.right-column {
background-color: #E7D0D8;
flex-direction: column;
margin: 0 auto;
width: 20%;
padding: 2em;
z-index: 1;
}

.icon-left,
.icon-right {
display: flex;
flex-direction: column;
justify-content: left;
color: white;
}


.icon-right div{
padding-bottom: 20px;
}

.icon-left span {
color: rgb(74, 15, 102);
}
.icon-right span {
color: rgb(74, 15, 102);
}

.left-icon-text,
.right-icon-text {
color: rgb(74, 15, 102);
}

.right-icon-text h3{
color: rgb(74, 15, 102);
}

.left-head-support,
.right-head-support {
display: flex;
flex-direction: row;
}

.left-right-column-text {
color: rgb(74, 15, 102);
}

.right-hr-head,
.left-hr-head {
width: 100%;
position: relative;
left: 0;
top: -20px;
height: 1px;
background-color: #ccc;
}

@media screen and (min-width: 320px) and (max-width: 960px) {
.container1 {
display: block;
width: 100%;
}

.icon-right,
.icon-left {
font-size: 15px;

}

.left-right-column-text {
font-size: 10px;
}

.left-column,
.right-column {
width: 90%;
}

.right-hr-head,
.left-hr-head {
display: none;
}
}



@media screen and (min-width: 800px) and (max-width: 1000px) {


p {
font-size: 10px;
}


}

@media screen and (max-width:1500px) {
h1 {
font-size: 40px;
}
}

@media screen and (max-width:1000px) {
h1 {
font-size: 30px;
}
}

@media screen and (max-width:1000px) {
p {
font-size: 20px;
}
}

@keyframes slidInTop {
from {
transform: translateY(-300PX);
}

to {
transform: translateY(0);
}
}

/* CONTAINER4 */
.container4 {
width: 100%;
display: flex;
margin: 0 auto;
justify-content: space-around;
}

.anpimg {
width: 200px;
padding: 30px;
margin: 0 auto;
padding-top: 50px;
position: absolute;
z-index: 9999;
left: 19.4%;

}
.img1{
height: 50px;
}

.gncimg {
position: absolute;
z-index: 999;
left: 1%;
top: 181.9%;
}

.img2 {
width: 50px;
z-index: 89;
}

.ecoimg {
width: 200px;
padding: 30px;
padding-top: 50px;
position: absolute;
z-index: 999;
left: 5%;
}




@media screen and (min-width: 320px) and (max-width: 1400px) {
.container4 {
display: flex;
margin: 0 auto;
justify-content: space-around;
width: 100%;
}
p{
font-size: 14px;
text-align: center;
}
}


@media screen and (max-width: 800px)  {
.container4 {
display: none;
}
}

@media screen and (min-width: 801px) and (max-width: 1000px){
.container4{
display: none;
}
}

.sea{
width: 100%;
height: 400px;
}
</style>