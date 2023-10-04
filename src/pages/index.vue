<template>
    <body>
        <h1>Boulangerie Rostan</h1> 
        <img src="https://placehold.co/1920x1080"/>
        <RouterLink to="/produits"><bouton>Venez decouvrir nos pâtisseries</bouton></RouterLink>
        <section id="contact">
        <h2>Contactez-moi</h2>
        <section id="L’ART DU BOULANGER-PÂTISSIER">
            <h2>L’ART DU BOULANGER-PÂTISSIER</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia ipsum veritatis ad?</p>
            <RouterLink to="/produits"><bouton>En savoir plus</bouton></RouterLink>
        </section>
        <form>
            <label for="name">Nom :</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email :</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message :</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Envoyer</button>
        </form>
    </section>

    </body>
</template>