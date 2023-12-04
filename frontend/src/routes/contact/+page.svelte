<html lang="fr">
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <meta charset="utf-8">
        <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Work+Sans:ital,wght@1,300&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css" integrity="sha512-MV7K8+y+gLIBoVD59lQIYicR65iaqukzvf/nwasF0nqhPay5w/9lJmVM2hMDcnK1OnMGCdVK+iQrJ7lzPJQd1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    </head>
</html>
<script>
    let nom;
    let sujet;
    let mail;  
    let numero;
    let message;
	import { prevent_default } from "svelte/internal";
    
</script>
<main>
<div class="container">
    <div class="image-column">
        <img src="https://www.emmamoorbynd.com/wp-content/uploads/bb-plugin/cache/ezgif.com-gif-maker2-1-1536x1536-square.jpg"  alt="image">
        <div>
            <span class="fa-solid fa-phone" style="font-size: 36px; margin-right: 10px;"></span>
            <span>0745123085</span></div>
            <br>
            <div>
            <span class="fa-solid fa-at" style="font-size: 36px; margin-right: 10px;"></span>
            <span> EMAIL <br>
                <a href="#">med.lina.jaber@gmail.com</a></span></div><br>
                <a href="https://www.facebook.com/profile.php?id=100089682795278"><i class="fa-brands fa-facebook fa-2xl"></i></a>Santélina
        </div>


<div class="right-container">
    <h2>Contact</h2>
    <hr>
    
        <p> Ecrivez ici votre message!</p>
        <form>
            <input type="text" placeholder="Votre nom" bind:value={nom} />
            <br /><br />
            <input type="text" placeholder="sujet" bind:value={sujet} />
            <br /><br />
            <input type="email" placeholder="Votre Mail" bind:value={mail} />
            <br /><br />
            <input type="text" placeholder="Votre Numéro" bind:value={numero} />
            <br /><br />
            <textarea class="field" placeholder="Votre Message" bind:value={message}></textarea>
            <br /><br />
            <div class="center">
            <input class="submit" type="submit" value="Envoyer message" />
            <p id="reussite"></p>
            </div>
        </form>
</div>

</div>
</main>
    <style>
        
        .container {
    display: flex;
    width: 100%;
    margin: 0 auto;
}
.right-container{
        width: 50%;
        height: 100%;
        margin: 0 auto;
        border: black;
        box-shadow:0 0 5px  ;
}
form{
        background-color: white;
        padding: 1.2em;
        box-sizing: border-box;
    }
    input, textarea{
        width: 100%;
        padding: 1.2em;
        box-sizing: border-box;
        outline: none;
        resize: none;
        background-color: #f7f3f3;
        border: #535555;
    }
    .center{
        text-align: left;
        width: 40%;
        border-radius: 2.5em ;
    }
    .field{
        height: 10.6em;
    }
    .submit{
        border-radius: 1.3em;
        background-color: #0a7713;
        border: none;
        width: 13.7;
        height: 2.5em;
        padding: 0.3em;
        color: white;
    }
.image-column {
    width: 40%;
}
img {
    width: 100%;
    height: auto;
}
hr{
    width: 30%;
    margin-left: 0;
}
h2{
    padding-left: 1.25em;
    font-family: 'Poppins', sans-serif;
    font-weight: 200;
    color: rgb(74, 15, 102);
    line-height: 1.2;
}
p{
    padding-left: 1.2em;
    font-weight: 300;
    color: #535555;
    line-height: 1.2;
}
.fa-solid {
    vertical-align: middle;
    color: rgb(74, 15, 102);
}
.fa-brands{
    color: rgb(74, 15, 102);
}
a{
    text-decoration: none;
    color: rgb(74, 15, 102);
}

@media screen and (min-width: 900px) and (max-width: 1800px){
    .container {
        width: 100%;
    }

}
@media screen and (min-width: 320px) and (max-width: 480px){
    .container {
        display: block;
    }
    .right-container{
        width: 100%;
    }
   
    .image-column{
        width: 100%;
    }
    
}
@media screen and (min-width: 481px) and (max-width: 900px){
    .container {
        display: block;
        width: 100%;
        
    }
    .right-container{
        width: 60%;
    }
    
    .image-column{
        width: 50%;
    }
}
</style>