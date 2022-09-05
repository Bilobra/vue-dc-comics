
<template>
    <header>
        <div class="container">

            <div class="nav-wrapper">

                <div class="logo">
                    <img src="../assets/dc-logo.png" alt="logo dc">
                </div>
                <nav class="nav">
                    <ul>
                        <li class="nav-link"><a href="#">characters</a></li>
                        <li class="nav-link"><a href="#">comics</a></li>
                        <li class="nav-link"><a href="#">movies</a></li>
                        <li class="nav-link"><a href="#">tv</a></li>
                        <li class="nav-link"><a href="#">games</a></li>
                        <li class="nav-link"><a href="#">collectibles</a></li>
                        <li class="nav-link"><a href="#">videos</a></li>
                        <li class="nav-link"><a href="#">fans</a></li>
                        <li class="nav-link"><a href="#">news</a></li>
                        <li class="nav-link"><a href="#">shop</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>
</template>



<script>
export default {

}
</script>

<style lang="scss" scoped>
header{
    padding: 60px 0;
}
.nav-wrapper{
    display: flex;
    justify-content: space-between;
    align-items: center;

    .nav{
        ul{
            display: flex;
            gap:1rem;
            text-transform: uppercase;
            font-size: 18px;
        
        }
    }
}
</style>