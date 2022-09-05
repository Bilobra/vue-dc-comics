<template>
    <section class="main_footer">
        <div class="container">
            <div class="row">
                <div class="col col-link">
                    <div class="">

                        <ul>
                            <li class="list-title">dc comics</li>
                            <li class="col-list-content"><a href="#">Characters</a></li>
                            <li class="col-list-content"><a href="#">Comics</a></li>
                            <li class="col-list-content"><a href="#">Movies</a></li>
                            <li class="col-list-content"><a href="#">Tv</a></li>
                            <li class="col-list-content"><a href="#">Games</a></li>
                            <li class="col-list-content"><a href="#">News</a></li>
                        </ul>

                        <ul>
                            <li class="list-title">shop</li>
                            <li class="col-list-content"><a href="#">shop DC</a></li>

                            <li class="col-list-content"><a href="#">shop DC Collectibles</a></li>

                        </ul>
                    </div>
                    <div class="">



                        <ul>
                            <li class="list-title">DC</li>
                            <li class="col-list-content"><a href="#">Terms Of Use</a></li>
                            <li class="col-list-content"><a href="#">Privacy policy(New)</a></li>
                            <li class="col-list-content"><a href="#">Ad Choises</a></li>
                            <li class="col-list-content"><a href="#">Adversting</a></li>
                            <li class="col-list-content"><a href="#">Jobs</a></li>
                            <li class="col-list-content"><a href="#">Subscriptions</a></li>
                            <li class="col-list-content"><a href="#">Talent Workshops</a></li>
                            <li class="col-list-content"><a href="#">CPSC Certificates</a></li>
                            <li class="col-list-content"><a href="#">Rattings</a></li>
                            <li class="col-list-content"><a href="#">Shop Help</a></li>
                            <li class="col-list-content"><a href="#">ontacts US</a></li>
                        </ul>
                    </div>
                    <div class="">



                        <ul>
                            <li class="list-title"><a href="#">Sities</a></li>
                            <li class="col-list-content"><a href="#">DC</a></li>
                            <li class="col-list-content"><a href="#">MAD Magazine</a></li>
                            <li class="col-list-content"><a href="#">DC Kids</a></li>
                            <li class="col-list-content"><a href="#">DC Universe</a></li>
                            <li class="col-list-content"><a href="#">DC Power Vista</a></li>

                        </ul>
                    </div>


                </div>
                <div class="col col-img-bg">
                    <div class="logo_footer">
                        <img src="../assets/dc-logo-bg.png" alt="logo bg">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.main_footer {
    background-image: url('../assets/footer-bg.jpg');
    background-size: cover;
    background-position: center;
    padding: 30px 0;
    height: 550px;


}

.row {
    display: flex;
    justify-content: space-between;
    height: 100%;

    .col-link {


        display: flex;
        flex-basis: 400px;
        gap: 30px;
        // flex-direction: column;

        ul {

            padding: 20px 0;

            .list_title {
                color: white;
                text-transform: uppercase;
                font-size: 20px;
            }

            .col-list-content {
                color: #627274;
                font-size: 18px;
                line-height: 20px;
                padding: 5px 0
            }



        }
    }
    .col-img-bg{
       .logo_footer{
        width: 90%;
       }
    }

    
}
</style>