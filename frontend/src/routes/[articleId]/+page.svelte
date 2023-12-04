
<script lang="ts">
    import type { PageData } from './$types'
    
    export let data: PageData;
    
    
    $: ({ article } = data)
    
    
    
    
    </script>

<form class="addarticle" action="?/updateArticle" method="POST">
    <div class="artdiv">
        <div class="artone">
            <h3>Editing: {article.title}</h3>
            <label for="title">Title</label>
            <input class="artext" type="text" id="title" name="title" value={article.title}/>
        </div>
    <div class="arttow">    
        <label for="content">Content</label>
        <textarea id="content" name="content" rows={5} value={article.content}/>
    </div>
        <button type="submit">update Article</button>
    </div>
</form>
















<style>




</style>