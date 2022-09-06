<template>
    <div class="card">
        <img :src="thumb" :alt="series">
        <h3>{{ series }}</h3>
        <h4>{{ price }}</h4>
    </div>
</template>

<script>
export default {
    props: {
        thumb: String,
        series: String,
        price: Number,

    }
}
</script>



<style lang="scss" scoped>
.card {
    flex-basis: calc(100% / 6 - 28px);
    display: flex;
    flex-direction: column;


    img {
        // width: 50%;
        height: 184px;
        opacity: 0.7;

        &:hover {
            transform: scale(1.1);
            border: 1px solid white;
            opacity:1;
        }
    }

    h3 {
        margin: 15px 0;
        color: white;
        text-transform: uppercase;
        font-size: 14px;
    }
}
</style>