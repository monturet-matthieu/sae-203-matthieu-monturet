<template>
  <img class="w-full mb-12" src="../../public/img/img_accueil.webp" alt="image de la page d'accueil">

    <div class="flex justify-center xl:space-x-40 xl:mx-48 md:mx-16 sm:mx-8 sm:flex-col md:flex-col lg:flex-col xl:flex-row">
      <div class="flex sm:justify-center">
        <div class="flex flex-col text-center bg-gray-100 rounded-t-xl sm:mb-24 max-w-3xl">
          <div class="flex flex-row mb-6">
            <img class="rounded-tl-3xl md:max-h-72 lg:max-h-72 xl:h-72 w-1/2" src="../../public/img/emile-parisien.webp" alt="Image du saxophoniste Emile Parisien">
            <img class="rounded-tr-3xl md:max-h-72 lg:max-h-72 xl:h-72 w-1/2" src="../../public/img/baptiste-herbin.webp" alt="Image du saxophoniste Baptiste Herbin">
          </div>
          <h3 class="text-2xl font-bold font-gothic text-blue-850 mx-2 mb-4">Retrouvez la liste des artistes présents à notre festival</h3>
          <p class="font-montserrat font-medium text-gray-900 mx-6 md:mx-16 mb-8 text-left">Baptiste Herbin, Emile Parisien... ces jazzmen reconnus joueront sur notre scène lors de représentations tout au long de la semaine !</p>
          <RouterLink class="flex justify-end mr-8 pb-10 space-x-2" to="/artistes">
            <button class="font-black font-gothic text-gray-900 text-xl">Découvrir</button>
            <ArrowNarrowRightIcon class="stroke-gray-900 w-8 h-8" />
          </RouterLink>
        </div>
      </div>
      <div class="flex sm:justify-center">
        <div class="flex flex-col text-center bg-gray-100 rounded-t-xl mb-24 xl:mb-24 max-w-3xl">
          <img class="rounded-t-3xl xl:h-72 md:max-h-72 lg:max-h-72 mb-6 w-full" src="../../public/img/img-programmation.webp" alt="Banderolle d'illustration">
          <h3 class="text-2xl font-bold font-gothic text-blue-850 mx-2 mb-12">Accédez au planning complet du festival</h3>
          <p class="font-montserrat font-medium text-gray-900 mx-6 md:mx-16 mb-8 text-left">Le programme des six jours complets du festival est disponible ! Découvrez à quel moment vos artistes favoris feront leur apparition.</p>
          <RouterLink class="flex justify-end mr-8 pb-10 space-x-2" to="/artistes">
            <button class="font-black font-gothic text-gray-900 text-xl">Découvrir</button>
            <ArrowNarrowRightIcon class="stroke-gray-900 w-8 h-8" />
          </RouterLink>
        </div>
      </div>
    </div>
  <div class="flex justify-center">
    <div class="flex flex-col text-center bg-gray-100 rounded-t-xl xl:mx-64 md:mx-16 sm:mx-8 mb-24 max-w-3xl">
      <img class="rounded-t-3xl xl:h-72 md:max-h-72 lg:max-h-72 mb-6 w-full" src="../../public/img/guide.webp" alt="Banderolle d'illustration">
      <h3 class="text-2xl font-bold font-gothic text-blue-850 mx-2 mb-12">Observez un aperçu de la base de création de l'identité du site</h3>
      <p class="font-montserrat font-medium text-gray-900 mx-6 md:mx-16 mb-8 text-left">Dans une démarche d'ouverture, nous vous proposons d'accéder à notre guide de style, qui nous a permis d'arriver aux différents résultats graphique du festival, dont ce site.</p>
      <RouterLink class="flex justify-end mr-8 pb-10 space-x-2" to="/guide">
        <button class="font-black font-gothic text-gray-900 text-xl">Découvrir</button>
        <ArrowNarrowRightIcon class="stroke-gray-900 w-8 h-8" />
      </RouterLink>
      </div>
    </div>
</template>

<script>
import { ArrowNarrowRightIcon} from '@heroicons/vue/outline'
export default {
  components: { ArrowNarrowRightIcon }
}
</script>