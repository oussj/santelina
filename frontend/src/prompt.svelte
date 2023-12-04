    <script>
        let showModal = true;
    
        function closeModal() {
        showModal = false;
        }
    
        function acceptConditions() {
        closeModal();
        }
        import { goto } from "$app/navigation"
        function handleClick() {
            goto('/Privacy');
        }
    </script>
    
    {#if showModal}
        <div class="modal">
        <div class="modal-content">
            <span class="close" on:click={closeModal}>&times;</span>
            <h2>Bienvenue sur notre site web!</h2>
            <p>Veuillez lire et accepter notre <a href="#" on:click={handleClick}> Politique de confidentialité </a> avant de continuer.</p>
            <button on:click={acceptConditions}>J'accepte</button>
        </div>
        </div>
    {/if}
    
    <style>
        .modal {
        display: flex;
        align-items: center;
        justify-content: center;
        position: fixed;
        z-index: 1;
        left: 0;
        top: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, 0.5);
        }
    
        .modal-content {
        background-color: #fefefe;
        padding: 20px;
        border: 1px solid #888;
        width: 80%;
        }
    
        .close {
        color: #aaa;
        float: right;
        font-size: 28px;
        font-weight: bold;
        cursor: pointer;
        }
    
        .close:hover {
        color: black;
        }
    
        button {
        background-color: #4caf50;
        color: white;
        padding: 10px 15px;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        }
    </style>
    