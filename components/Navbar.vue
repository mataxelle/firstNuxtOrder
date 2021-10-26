<template>
    <div>
        <nav class="navbar navbar-expand navbar-dark bg-info">
            <ul class="navbar-nav mx-auto flex-row">
                <li class="nav-item">
                    <nuxt-link class="nav-link" aria-current="page" to="/">Accueil</nuxt-link>
                </li>
                <li class="nav-item">
                    <nuxt-link class="nav-link" aria-current="page" to="/commandes">Commande</nuxt-link>
                </li>
                <li class="nav-item">
                    <nuxt-link class="nav-link" aria-current="page" to="/panier">Panier</nuxt-link>
                </li>
            </ul>
        </nav>
    </div>
</template>