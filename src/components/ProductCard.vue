<template>
    <div class="card">
        <img :src="thumb" :alt="series">
        <h3>{{series}}</h3>
        <h4>{{price}}</h4>
    </div>
</template>

<script>
export default {
    props:{
        thumb: String,
        series : String,
        price : Number,

    }
}
</script>



<style lang="scss" scoped>
.card {
    padding: 5px;
    background-color: white;
}
</style>