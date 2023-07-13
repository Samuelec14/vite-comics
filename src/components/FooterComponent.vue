<script>
export default {
    name: "FooterComponent",
    data() {
    return{

    }
    },
    methods: {

    }
}
</script>

<template>

    <footer class="debug">
        <section id="sec-1-footer" class="debug">
            <div class="container">
                <div class="flex-container">
                    <div>
                        <div>
                            prova
                        </div>
                        <div>
                            prova
                        </div>
                    </div>
    
                    <div>
                        <div>
                            prova
                        </div>
                    </div>
    
                    <div>
                        <div>
                            prova
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="sec-2-footer" class="debug">
            
        </section>
    </footer>

</template>

<style lang="scss" scoped>

footer{
    text-align: center;
    

    #sec-1-footer{
        height: 400px;
        background-color: lightgray;

        .container{


            .flex-container{
                padding: 50px ;

                div{
                    margin-inline-end: 100px;

                    span{

                    }
                }
            }
        }
    }

    #sec-2-footer{
        height: 130px;
        background-color: gray;
    }
}

</style>