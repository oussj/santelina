<script>
  import axios from 'axios';
  import { onMount } from 'svelte';

  let message = 'Chargement...';

  onMount(async () => {
    try {
      const response = await axios.get('http://localhost:8000/article');
      message = response.data;
    } catch (error) {
      console.error(error);
      message = 'Erreur lors du chargement des données';
    }
  });
</script>

<article>
  <h1>{message}</h1>
</article>