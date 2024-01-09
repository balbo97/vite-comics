<script>
export default {
    name: 'AppFooter',
    data() {
        return {

        }
    },
}
</script>

<template lang="">
    <footer>
        <div class="top-footer">
            <div class="container-sm">
                <div class="row">
                    <div class="col">
                        
                    </div>
                    
                </div>
            </div>
        </div>
        <div class="bottom-footer">
            <div class="container-sm">
                <div class="row">
                    <div class="col">
                        <div class="content d-flex justify-content-between">

                            <button type="button" class="btn btn-outline-primary">SIGN-UP NOW!</button>
                            <div class="social-media d-flex align-items-center">
                                <p>FOLLOW US</p>
                                <div class="images">

                                    <img src="../assets/img/footer-facebook.png" alt="">
                                    <img src="../assets/img/footer-periscope.png" alt="">
                                    <img src="../assets/img/footer-pinterest.png" alt="">
                                    <img src="../assets/img/footer-twitter.png" alt="">
                                    <img src="../assets/img/footer-youtube.png" alt="">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
.top-footer {
    background-image: url('../assets/img/footer-bg.jpg');
    height: 400px;

    .col {
        background-image: url('../assets/img/dc-logo-bg.png');
        background-position: right;
        background-repeat: no-repeat;
        height: 400px;
    }
}

.bottom-footer {
    background-color: rgb(35, 35, 35);
    color: white;
    padding: 40px 0;

    .social-media {
        p {
            margin-bottom: 0;
            margin-right: 20px;
            color: rgb(1, 110, 219);
        }

        img {
            margin-left: 10px;
        }
    }


}
</style>