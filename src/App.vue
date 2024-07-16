<template>
  <div class="container  is-fluid columns">
    <SideNavigator />
    <div class="box column auto has-background-dark">
      <PlayerComponent />
      <div class="columns mt-5">
        <div class="column my-auto">
          <figure class="image is-256x256">
            <img src="https://bulma.io/assets/images/placeholders/256x256.png" />
          </figure>
          <nav class="level card mt-2 p-3 is-primary">
            <div class="level-item has-text-centered">
              <div>
                <p class="heading">Oyentes</p>
                <p class="title">3,456</p>
              </div>
            </div>
            <div class="level-item has-text-centered">
              <div>
                <p class="heading">Compartidos</p>
                <p class="title">456K</p>
              </div>
            </div>
            <div class="level-item has-text-centered">
              <div>
                <p class="heading">Likes</p>
                <p class="title">789</p>
              </div>
            </div>
          </nav>
        </div>
        <div class="column mx-auto">

          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio ea architecto vitae ratione repellat dicta
            commodi aspernatur aliquid quidem nobis. Corporis nisi hic molestiae illo voluptatem. Excepturi totam
            repellat
            debitis.
            Perspiciatis recusandae tempora delectus incidunt eius saepe nobis ea. Nihil asperiores maxime sapiente
            adipisci corrupti facere quis perferendis officiis doloremque itaque quae a temporibus blanditiis eum
            corporis
            saepe, placeat at.
          </p>
        </div>
        <div class="column m-2 p-0">
          <div class="about card p-5">
            <h1 class="title">Acerca de...</h1>
            <figure class="image is-128x128 mx-auto">
              <img class="is-rounded" src="https://bulma.io/assets/images/placeholders/128x128.png" />
            </figure>
            <p class="mt-5">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatum quaerat ab atque
              praesentium. Unde libero officia odio temporibus natus nihil reprehenderit molestias labore adipisci ipsa,
              numquam maxime soluta voluptatum et.</p>
          </div>

        </div>
      </div>

    </div>
  </div>
</template>

<script>
import SideNavigator from '@/components/SideNavigator.vue'
import PlayerComponent from '@/components/PlayerComponent.vue'

export default {
  name: 'App',
  components: {
    SideNavigator,
    PlayerComponent
  },
  data() {
    return {}
  }
}
</script>

<style>
#app {
  margin-top: 16px;
}
</style>
