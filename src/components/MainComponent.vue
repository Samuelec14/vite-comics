<script>
export default {
    name: "MainComponent",
    data() {
    return{

    }
    },
    methods: {

    }
}
</script>

<template>

    <main>
        
            <section id="sec-1-main">
                <div class="container">
                    <span> content here </span>
                </div>
            </section>

            <section id="sec-2-main"> 
                <div class="container">
                    <div class="row">
                        <div class="col-2-10">
                            <span>digital comics</span>
                        </div>
                        <div class="col-2-10">
                            <span>dc merchandise</span>
                        </div>
                        <div class="col-2-10">
                            <span>subscription</span>
                        </div>
                        <div class="col-2-10">
                            <span>comic shop locator</span>
                        </div>
                        <div class="col-2-10">
                            <span>dc power visa</span>
                        </div>
                    </div>
                </div>
            </section>

    </main>

</template>

<style lang="scss" scoped>

main{
    text-align: center;


        #sec-1-main{
            height: 130px;
            line-height: 120px;
            background-color: rgb(28, 28, 28);

    
            span{
                color: white;
                text-transform: uppercase;
            }
        }

        #sec-2-main{
            background-color: rgb(2, 130, 249);
            height: 170px;

            .container{

                .col-2-10{
                    width: calc((100% / 10) * 5);
                    line-height: 170px;
                    
                    span{
                        color: white;
                        text-transform: uppercase;
                        font-size: small;
                    }
                }
            }
        }

}


</style>