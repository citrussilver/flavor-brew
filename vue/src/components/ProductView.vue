<template>
    <div>
        <Header />
        <div class="grid md:grid-cols-2 sm:grid-cols-1 md:gap-4">
        <!-- <div class="product-grid grid sm:grid-cols-1 md:gap-4s"> -->
            <div>
                <img src="../assets/img/ratio_six_detail.jpg" alt="item_image">
            </div>
            <div class="cream-white px-8 flex-col gap-2">
                <h1 class="xl:text-3xl xl:mb-6 lg:text-2x pt-4">Ratio Six</h1>
                <div class="mb-4">$365.00</div>
                <div class="mb-6">
                    <span class="material-icons">star</span>
                    <span class="material-icons">star</span>
                    <span class="material-icons">star</span>
                    <span class="material-icons">star</span>
                    <span class="material-icons">star_border</span>
                </div>
                <hr class="w-4/6"/>
                <div class="mb-4">
                    <p class="w-7/12">Thanks to Ratio Six, world-class coffee is more accessible than ever. Engineered with the brewing precision of the Ratio Eight, the Six offers the one-button convenience of its bigger sibling with a leaner form and lighter price.</p>
                </div>
                <div class="special-font uppercase mb-2"><span class="material-icons md-icon-size">water_drop</span>BPA-free water tank</div>
                <div class="special-font uppercase mb-2"><span class="material-icons md-icon-size">flag</span>Designed in Portland, Oregon</div>
                <div class="special-font uppercase mb-2"><span class="mb-8 material-icons md-icon-size">workspace_premium</span>SCA Certified Home Brewer Award</div>
                <router-link :to="{ name: 'ProductView'}">
                    <div class="border border-green-900 p-4 text-center hover:bg-green-900 w-1/3 whitespace-nowrap hover:text-white text-green-900">
                        Customize your Ratio
                    </div>
                </router-link>
            </div>
        </div>
    </div>    
</template>

<script setup>
import Header from '../components/Header.vue';
</script>

<style>
.product-grid {
    display: grid;
    grid-template-columns: 0.60fr 0.40fr;
    gap: 1.5rem;
}

.md-icon-size {
    position: relative;
    top: 0.4rem;
    margin-right: 0.5rem;
}
</style>