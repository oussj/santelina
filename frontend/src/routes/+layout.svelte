<script>  
    import Navbar from "../Navbar.svelte";
    import Hero from "../Hero.svelte";
    import Footer from "../footer.svelte";    
    import WelcomeModal from "../prompt.svelte";

</script>

<Hero />
<Navbar />
<slot />
<Footer />
    <WelcomeModal />