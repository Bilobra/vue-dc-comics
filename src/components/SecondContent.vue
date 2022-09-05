<template>
    <section class="light_section">
        <div class="container">
            <ul>
                <li class="content-link">

                    <figure class="img_content">
                        <img src="../assets/buy-comics-digital-comics.png" alt="digitalComics">
                    </figure>
                    <div>
                        <a href="#">
                            digital comics
                        </a>

                    </div>

                </li>
                <li class="content-link">

                    <figure class="img_content">
                        <img src="../assets/buy-comics-merchandise.png" alt="digitalComics">
                    </figure>
                    <div>
                        <a href="#">
                            dc merchandise
                        </a>

                    </div>

                </li>
                <li class="content-link">

                    <figure class="img_content">
                        <img src="../assets/buy-comics-subscriptions.png" alt="digitalComics">
                    </figure>
                    <div>
                        <a href="#">
                            subscription
                        </a>

                    </div>

                </li>
                <li class="content-link">

                    <figure class="img_content">
                        <img src="../assets/buy-comics-shop-locator.png" alt="digitalComics">
                    </figure>
                    <div>
                        <a href="#">
                            comic shop locator
                        </a>

                    </div>

                </li>
                <li class="content-link">

                    <figure class="img_content">
                        <img src="../assets/buy-dc-power-visa.svg" alt="digitalComics">
                    </figure>
                    <div>
                        <a href="#">
                            comic shop locator
                        </a>

                    </div>

                </li>

            </ul>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import '@/style/variables';

.light_section {
    background-color: $light-blue;
    padding: 75px 0;
    color: white;

    ul {
        display: flex;
        align-items: center;
        
        gap: 25px;

        .content-link {
            display: flex;
            align-items: center;
            font-size: 18px;
            text-transform: uppercase;
            gap: 20px;
            

            .img_content {
                width: 50px;
                height: 60px;
                
            }
        }
    }
}
</style>