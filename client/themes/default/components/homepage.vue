<template lang="pug">
  v-main.homepage
    v-container(fluid).banner.pa-0
      .content(slot="content")
        v-container.pa-16
          v-row
            v-col
              .text-h4.font-weight-bold.text-center.white--text
                | Wiki Élysée - Space Station 13
                br
              .text-h6.text-center
                | Serveur HRP SS13
          v-row.mt-4.px-10
            v-col
              .text-md.text-center
                | Le gouvernement Solarien a mandaté la mégacorporation Space Express pour envoyer les premières missions d'exploration de l'espace profond.
                | Votre objectif : découvrir les planètes habitables et industrialisables, rencontrer les premières espèces xéno intelligentes, et
                | survivre dans l'environnement hostile qu'est l'espace.
      //v-img(src='/_assets/img/banner.png')

</template>

<style lang="scss">
  .homepage+main {
    display: none;
  }

  .banner {
    background-image: url('../')
    .v-image {
      position: absolute;
      top: 0;
      left: 0;
      height: 100%;
      width: 100%;
    }
  }
</style>
