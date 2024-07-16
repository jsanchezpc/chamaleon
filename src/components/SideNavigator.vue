<template>
    <aside class="menu column is-one-fifth mt-0 pt-0">
        <div class="field is-grouped mb-5">
            <p class="control is-expanded">
                <input class="input" type="text" placeholder="Busca podcasts">
            </p>
            <p class="control">
                <button class="button is-primary">
                    Buscar
                </button>
            </p>
        </div>

        <p class="menu-label">Tú (kkissta)</p>
        <ul class="menu-list">
            <li><a>Perfil</a></li>
            <li><a>Notificaciones</a></li>
            <li><a>Favoritos</a></li>
            <li><a>Subir</a></li>

        </ul>
        <p class="menu-label">Podcasts</p>

        <ul class="menu-list">
            <li><a>Talento</a></li>
            <li>
                <a class="menu-label">Siguiendo (+143)</a>
                <ul>
                    <li class="media mb-0">
                        <a class="columns my-auto">
                            <div class="column is-2 ml-0 ">
                                <figure class="image is-32x32">
                                    <img src="https://bulma.io/assets/images/placeholders/96x96.png"
                                        alt="Placeholder image" />
                                </figure>
                            </div>
                            <div class="column auto ml-4 my-auto">
                                Kkissta
                            </div>
                        </a>
                    </li>
                    <li class="media mb-0">
                        <a class="columns my-auto">
                            <div class="column is-2 ml-0 ">
                                <figure class="image is-32x32">
                                    <img src="https://bulma.io/assets/images/placeholders/96x96.png"
                                        alt="Placeholder image" />
                                </figure>
                            </div>
                            <div class="column auto ml-4 my-auto">
                                funalito
                            </div>
                        </a>
                    </li>
                    <li class="media mb-0">
                        <a class="columns my-auto">
                            <div class="column is-2 ml-0 ">
                                <figure class="image is-32x32">
                                    <img src="https://bulma.io/assets/images/placeholders/96x96.png"
                                        alt="Placeholder image" />
                                </figure>
                            </div>
                            <div class="column auto ml-4 my-auto">
                                El rincón de Fulanita
                            </div>
                        </a>
                    </li>
                </ul>
            </li>
            <li><a>Descubrir</a></li>
        </ul>
        <p class="menu-label">Cuenta</p>
        <ul class="menu-list">
            <li><a>Ajustes</a></li>
            <li><a>Salir</a></li>
        </ul>
        <div class="container has-text-centered">
            Chamaleon © 2024
        </div>
    </aside>
</template>

<script>
export default {
    name: 'SideNavigator'
}
</script>