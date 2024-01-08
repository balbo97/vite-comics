<script>
export default {
    name: 'AppMain',
    data() {
        return {

        }
    },
}
</script>

<template lang="">
    <main>
        <div class="bg-dark">

            <div class="container-sm">
                <div class="row">
                    <div class="col">
                        <div class="content py-5 text-light">
                        -- > CONTENT GOES HERE < --
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="buy_comics">
            <div class="container-sm">
                <div class="row">
                    <div class="col">
                        <div class="images d-flex justify-content-around">

                            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                            <img src="../assets/img/buy-comics-merchandise.png" alt="">
                            <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                            <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                            <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                        </div>

                    </div>
                </div>
            </div>
        </div>
    </main>
</template>

<style lang="scss">
main {

    margin-top: 3px;

    .buy_comics {
        background-color: rgb(1, 110, 219);


        .images {
            height: 150px;
            padding: 50px 0;

            img {
                max-width: 100%;
                max-height: 100%;
            }
        }

    }
}
</style>