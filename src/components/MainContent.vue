<template>
    <section class="black_section">
        <div class="container">
            <div class="main_content">
                <ProductCard v-for = "(card,i) in CardsArray" :key="i" :thumb="card.thumb" :series="card.series" :price="card.price">
                </ProductCard>
            </div>
        </div>

    </section>
</template>

<script>

import CardsArray from '../ArrayCard'
import ProductCard from './ProductCard.vue'

export default {
    components:{
        ProductCard,
    },
    data() {
        return {
            CardsArray,
        }
    }
}
</script>

<style lang="scss" scoped>
.black_section {
    background-color: black;
    padding: 70px 0;
}

.main_content {

    display: grid;
    grid-template-columns: repeat(6, 1fr);

   
}
</style>