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

    <footer>
        <section id="sec-1-footer">
            <div class="container">
                <div class="flex-container">
                    <div>
                        <div>
                            <h2>dc comics</h2>
                            <ul>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                            </ul>
                        </div>
                        <div id="">
                            <h2>shop</h2>
                            <ul>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                            </ul>
                        </div>
                    </div>
    
                    <div>
                        <div>
                            <h2>dc</h2>
                            <ul>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                            </ul>
                        </div>
                    </div>
    
                    <div>
                        <div>
                            <h2>sites</h2>
                            <ul>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                                <li>DC Comics</li>
                            </ul>
                        </div>
                    </div>
                    <div class="img-container">
                        <img src="../assets/img/dc-logo-bg.png" alt="">
                    </div>
                </div>
            </div>
        </section>
        <section id="sec-2-footer">
            
        </section>
    </footer>

</template>

<style lang="scss" scoped>

footer{
    text-align: center;
    

    #sec-1-footer{
        background-image: url(../assets/img/footer-bg.jpg);
        background-size: cover;
        text-align: left;
        height: 380px;

        .container{


            .flex-container{
                padding: 20px ;


                >div{
                    margin-inline-end: 100px;

                    >div{



                        h2{
                            font-size: 27px;
                            padding: 18px 0;
                            text-transform: uppercase;
                            color: white;
                        }
                        li{
                            list-style: none;
                            color: gray;
                        }
                    }
                }
            }
            .img-container{
                height: 380px;
                width: 200px;

                .img{
                    width: 130%;
                }
            }
        }
    }

    #sec-2-footer{
        height: 130px;
        background-color: rgb(48, 48, 48);
    }
}

</style>