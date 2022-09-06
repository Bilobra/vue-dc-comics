<template>
    <section class="black_section">
        <div class="container">
            <div class="main_content">
                <div class="card">

                </div>
            </div>
        </div>

    </section>
</template>

<script>

import CardsArray from '../ArrayCard'

export default {
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

    .card {
        padding: 5px;
        background-color: white;
    }
}
</style>