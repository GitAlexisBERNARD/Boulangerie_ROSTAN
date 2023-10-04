<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>
<template>
    <header id="header">
        <div>
            <div>
                <div>
                    <a>
                        <img src="#" alt="Logo">
                    </a>
                </div>
                <div>
                    <nav>
                    <ul>
                        <li>
                            <RouterLink to="/apropos">À propos</RouterLink>
                        </li>
                        <li>
                            <RouterLink to="/horaires">Horaires</RouterLink>
                        </li>
                        <li>
                            <RouterLink to="/produits">Produits</RouterLink>
                        </li>
                    </ul>
                </nav>
            </div>
        </div>
    </div>
</header>
</template>