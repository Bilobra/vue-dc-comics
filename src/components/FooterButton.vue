<template>
    <section class="footer">
        .<div class="container">
            <div class="row">
                <div>
                    <button class="button_col">
                        <a href="#">sign-up now!</a>
                    </button>
                </div>
                <div class="col">
                    <ul>
                        <li class="follow_content">
                            <a href="#">
                                Follow us
                            </a>
                        </li>
                        <li class="icon-content">
                            <a href="#">
                                <img src="../assets/footer-twitter.png" alt="fb">
                            </a>
                        </li>
                        <li class="icon-content">
                            <a href="#">
                                <img src="../assets/footer-youtube.png" alt="fb">
                            </a>
                        </li>
                        <li class="icon-content">
                            <a href="#">
                                <img src="../assets/footer-pinterest.png" alt="fb">
                            </a>
                        </li>
                        <li class="icon-content">
                            <a href="#">
                                <img src="../assets/footer-periscope.png" alt="fb">
                            </a>
                        </li>
                        <li class="icon-content">
                            <a href="#">
                                <img src="../assets/footer-facebook.png" alt="fb">
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default{

    }
</script>

<style lang="scss" scoped>
    .footer{
        background-color: #303030;
    }
    .row{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 15px 0;

        .button_col{
            line-height: 20px;
            padding:15px 20px;
            border: 1px solid #0282F9;
            font-size: 20px;
            text-transform: uppercase;
            background-color: transparent;
           
            a{
                color:white;
            }
            
        }
    }
    .col{
        ul{
            display: flex;
            align-items: center;
            align-content: center;
            gap:20px;

            .follow_content{
                color: #0282F9;
                font-size: 22px;
                text-transform: uppercase;
                font-weight: 600;
            }
        }
    }
</style>