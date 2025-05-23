<template>
    <div class="container-fluid fons_projecte align-items-center justify-content-center">
        <div class="text-center m-5 p-5">
            <h1 class="text-white">PROYECTOS</h1>
        </div>
        <div class="row m-5 align-items-center justify-content-center limit-80">
            <div @click="goToCientifiks" class="card m-5 rounded-5 fons_card text-white" style="width: 30rem; cursor: pointer;">
                <h1 class="text-center p-4">Cientifiks (LetteRRain)</h1>
                <img :src="'/img/Screenshot_Cientifiks.png'" class="card-img-top mt-2 rounded-5" alt="...">
                <div class="card-body">
                    <p class="card-text text-center">HTML, CSS, Javascript y PHP</p>
                </div>
            </div>

            <div @click="goToMangaWeekend" class="card m-5 rounded-5 fons_card text-white" style="width: 30rem; cursor: pointer; ">
                <h1 class="text-center p-4">Manga Weekend</h1>
                <img :src="'/img/Screenshot_MW.png'" class="card-img-top mt-2 rounded-5" alt="no furula">
                <div class="card-body">
                    <p class="card-text text-center">VUE, Laravel, Bootstrap</p>
                </div>
            </div>
            <div class="card m-5 rounded-5 fons_card text-white" style="width: 30rem;">
                <h1 class="text-center p-4">Sing & Drink</h1>
                <img :src="'/img/sing_drink.png'" class="card-img-top mt-2 rounded-5" alt="...">
                <div class="card-body">
                    <p class="card-text text-center">VUE, Laravel, Bootstrap, Docker y Mapbox</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>

export default {
  methods: {
    goToCientifiks() {
      window.open('https://cientifiks.erfanribas.me', '_blank');
    },

    goToMangaWeekend() {
      window.open('https://mangaweekend.nataliacm.me', '_blank');
    }
  }
}
</script>

<style scoped></style>