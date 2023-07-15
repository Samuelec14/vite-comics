<script>
export default {
    name: "HeaderComponent",
    data() {
    return{

    }
    },
    methods: {

    }
}
</script>

<template>
    <header>
        <div class="container">
            <div class="row">
    
                <div id="header-lt-col" class="col-4">
                    <div class="img-container">
                        <img src="../assets/img/dc-logo.png" alt="">
                    </div>
                </div>
    
                <div id="header-rt-col" class="col-8">
                    <span>characters</span>
                    <span>comics</span>
                    <span>movies</span>
                    <span>tv</span>
                    <span>games</span>
                    <span>collectibles</span>
                    <span>videos</span>
                    <span>fans</span>
                    <span>news</span>
                    <span>shop</span>
    
                </div>
    
            </div>
        </div>
        <div class="jumbotron">
            
        </div>
    </header>

</template>

<style lang="scss" scoped>

header{
    text-align: center;
    background-color: white;

    .container{
        .row{
            height: 130px;

            #header-lt-col{
                padding: 15px;

                .img-container{
                    width: 27%;
                }

            }
            #header-rt-col{
                line-height: 120px;
                text-align: right;
    
                span{
                    padding: 9px 12px;
                    text-transform: uppercase;
                    font-size: small;
                    font-weight: 600;
                    color: rgb(28, 28, 28);
                }
            }
        }
    }
    .jumbotron{
        background-image: url(../assets/img/jumbotron.jpg);
        height: 400px;
    }
    
}


</style>