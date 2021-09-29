<template id="bg">


  <div  class="q-pa-md">
    <q-carousel
      v-model="slide"
      vertical
      transition-prev="slide-down"
      transition-next="slide-up"
      swipeable
      animated
      control-color="white"
      navigation-icon="radio_button_unchecked"
      navigation
      padding
      arrows
      height="600px"
      class="bg-red text-white shadow-1 rounded-borders"
    >
    
      <q-carousel-slide name="speed" class="column no-wrap flex-center">
        <q-icon name="speed" size="56px" />
        <div id="color1" class="q-mt-md text-center">
          Bienvenue sur ce (superbe) site fait à la va-vite pour l'occasion histoire de faire un truc un peu plus original.
          <br>
            En soit il sert pas à grand chose si ce n'est ajouter une couche de SUSPENSE...
        </div>
      </q-carousel-slide>
      <q-carousel-slide name="wtf" class="column no-wrap flex-center">
        <q-icon name="not_listed_location" size="56px" />
        <div id="color2" class="q-mt-md text-center">
                    Alors arrive la partie "complexe" pour accéder à la SURPRISE.

        </div>
      </q-carousel-slide>
      <q-carousel-slide name="mail" class="column no-wrap flex-center">
        <q-icon name="mail" size="56px" />
        <div id="color3" class="q-mt-md text-center">
            Il va falloir que tu te rendes sur <a href="https://account.protonmail.com/login">ce site</a> et que tu te connectes avec les identifiants suivants:
            <div id="color3">jamaisplus2023@protonmail.com</div>
            <br>
            <div id="color3">Le mot de passe quant à lui correspond aux trois animaux de ma super histoire que je t'ai racontée pour t'endormir.</div>
            <br>
            <div id="color3">A toi de t'en souvenir! Et dans le bon ordre! Par exemple si mon histoire impliquait un chien, un chat et une pie alors le mot de passe serait chienchatpie</div>

        </div>
      </q-carousel-slide>
      <q-carousel-slide name="key" class="column no-wrap flex-center">
        <q-icon name="key" size="56px" />
        <div id="color4" class="q-mt-md text-center">
          Bon et si vraiment tu trouves pas voilà un <a href="https://imgur.com/a/OQb0Wt1"> indice. </a>
        </div>
      </q-carousel-slide>

      <q-carousel-slide name="bonus" class="column no-wrap flex-center">
        <q-video
          class="absolute-full"
          src="https://www.youtube.com/embed/jcTn_3JJxwI"
        />

      </q-carousel-slide>
    </q-carousel>
  </div>
</template>


<script>


import { ref } from 'vue'

export default {
  setup () {
    return {
      slide: ref('speed'),
      fullscreen: ref(false)
    }
  }
}

</script>

<style>
  #color1 {
      font-family: "sl";
      font-size: 40px;
    margin-bottom: 5%;
  }

    #color2 {
      font-family: "inna";
      font-size: 40px;
    margin-bottom: 5%;
  }

  #color3 {
      font-family: "sl";
      font-size: 30px;
    
  }

  #color4 {
      font-family: "ana";
      font-size: 40px;
    margin-bottom: 5%;
  }

  body
  {
      background-color: black;
  }
</style>