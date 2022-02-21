<template>
  <div>
      <Header />
      <section id="pointers">
          <div class="p-7 flex justify-center font-bold text-3xl mb-2">The best part of your day just got better.</div>
          <div class="p-8 grid grid-cols-1 sm:grid-cols-1 md:grid-cols-3 lg:grid-cols-3 xl:grid-cols-3 gap-5">
            <!--Card 1-->
            <div class="overflow-hidden">
              <img class="w-full" src="../assets/img/rt-button-dark.webp" alt="Mountain">
              <div class="px-6 py-4">
                <div class="font-bold text-2xl mb-2 text-center">Simplify your routine.</div>
                <p class="text-gray-700 text-base text-center">
                  Our modern coffee makers removes variables like water temperature, extraction time, and pour over pattern so you can worry less about making your coffee, and more about drinking it.
                </p>
              </div>
            </div>
            <!--Card 2-->
            <div class="overflow-hidden">
              <img class="w-full" src="../assets/img/rt-brewing-wt.webp" alt="River">
              <div class="px-6 py-4">
                <div class="font-bold text-2xl mb-2 text-center">Elevate your taste.</div>
                <p class="text-gray-700 text-base text-center">
                  Making coffee at home or office shouldn’t feel like a compromise. We’ve engineered a pour over style system with the precision of high-end espresso machines. You’ll taste the difference.
                </p>
              </div>
            </div>

            <!--Card 3-->
            <div class="overflow-hidden">
              <img class="w-full" src="../assets/img/rt-tank-Silver.webp" alt="Forest">
              <div class="px-6 py-4">
                <div class="font-bold text-2xl mb-2 text-center">Enjoy it for life.</div>
                <p class="text-gray-700 text-base text-center">
                  We avoid things like plastic screws, tabs, or pods. We use materials like cast metal, handblown borosilicate glass, and real hardwoods, and back every Ratio coffee machine with a 5 year warranty.
                </p>
              </div>
            </div>
          </div>
      </section>
      <section id="testimonials">
        <div id="carouselExampleControls" class="carousel slide relative" data-bs-ride="carousel">
          <div class="carousel-inner relative w-full overflow-hidden">
            <div style="background-color: #f7f3ee;" class="carousel-item active relative float-left w-full">
              <div style="background-color: #f7f3ee; min-height: 30.6rem" class="flex items-center justify-center">
                <p class="text-2xl italic text-center">
                  &#8220;Make mornings glamorous with this minimalist coffee maker that blends perfectly<br/>with any kitchen decor.&#8221;<br/><br/>
                  <span class="font-bold">Celica</span>
                </p>
              </div>
            </div>
            <div class="carousel-item relative float-left w-full">
              <div style="background-color: #f7f3ee; min-height: 30.6rem" class="flex items-center justify-center">
                <p class="text-2xl italic text-center">
                  &#8220;The Flavor Brew Eight doesn't brew a fantastic cup of drip coffee. It brews a fantastic cup <br/>of pour-over coffee&#8221;
                  <br/><br/>
                  <span class="font-bold">Coffee Patrol</span>
                </p>
              </div>
            </div>
            <div class="carousel-item relative float-left w-full">
              <div style="background-color: #f7f3ee; min-height: 30.6rem" class="flex items-center justify-center">
                <p class="text-2xl italic text-center">
                  &#8220;The Flavor Brew Six perfects pour-over coffee at the press of a button...to deliver the taste<br/>of manual coffee &#225; la machine.&#8221;
                  <br/><br/>
                  <span class="font-bold">Brew Station</span>
                </p>
              </div>
            </div>
          </div>
          <button
            class="carousel-control-prev absolute top-0 bottom-0 flex items-center justify-center p-0 text-center border-0 hover:outline-none hover:no-underline focus:outline-none focus:no-underline left-0"
            type="button"
            data-bs-target="#carouselExampleControls"
            data-bs-slide="prev"
          >
            <span class="material-icons text-black">navigate_before</span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next absolute top-0 bottom-0 flex items-center justify-center p-0 text-center border-0 hover:outline-none hover:no-underline focus:outline-none focus:no-underline right-0"
            type="button"
            data-bs-target="#carouselExampleControls"
            data-bs-slide="next"
          >
            <span class="material-icons text-black">navigate_next</span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </section>
      <section id="line-up" class="mt-16">
          <div class="p-7 font-bold text-3xl mb-2">
            <p class="text-center mb-4">Meet the Flavor Brew line-up.</p>
            <p class="2xl:px-80 md:px-40 text-gray-700 text-xl text-center">
              Every Ratio machine is inspired by the beautiful ritual of manual brewing, often called pour over. Many of us love the taste of pour over but not the attention to detail and precision required for a consistent result. Enter Ratio.
            </p>
          </div>
          <div class="lg:px-32 p-7 grid grid-cols-1 sm:grid-cols-1 md:grid-cols-3 lg:grid-cols-3 xl:grid-cols-3 gap-5">
            <!--Card 1-->
            <div class="overflow-hidden">
              <img class="w-full" src="../assets/img/rt6-black-A3_360x.webp" alt="Mountain">
              <div class="px-6 py-4">
                <h5 class="text-center">SCA AWARD WINNER</h5>
                <div class="font-bold text-xl mb-2 text-center">Ratio Six</div>
              </div>
            </div>
            <!--Card 2-->
            <div class="overflow-hidden">
              <img class="w-full" src="../assets/img/rt8-white-walnut-glass-.webp" alt="River">
              <div class="px-6 py-4">
                <h5 class="text-center">OUR BEST-SELLING ORIGINAL</h5>
                <div class="font-bold text-xl mb-2 text-center">Ratio Eight</div>
              </div>
            </div>

            <!--Card 3-->
            <div class="overflow-hidden">
              <img class="w-full" src="../assets/img/rt-silver-parawood-thermal-A1_360x.webp" alt="Forest">
              <div class="px-6 py-4">
                <h5 class="text-center">THE COMPLETE PACKAGE</h5>
                <div class="font-bold text-xl mb-2 text-center">Ratio Eight Thermal Set</div>
              </div>
            </div>
          </div>
      </section>
  </div>
</template>

<script setup>
import Header from '../components/Header.vue';
</script>

<style>

#sticky-header-wrap {
  height: 4.875rem;
  width: 100%;
}

#nav-items {
  color: var(--colorTextBody);
}

.page-width {
  padding: 0 2.5;
  max-width: 1300px;
  margin: 0 auto;
}


</style>