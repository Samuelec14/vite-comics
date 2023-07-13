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
                            <h2>dc comics</h2>
                            <ul>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                            </ul>
                        </div>
                        <div id="">
                            <h2>shop</h2>
                            <ul>
                                <li>sda</li>
                                <li>sda</li>
                            </ul>
                        </div>
                    </div>
    
                    <div>
                        <div>
                            <h2>dc</h2>
                            <ul>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                            </ul>
                        </div>
                    </div>
    
                    <div>
                        <div>
                            <h2>sites</h2>
                            <ul>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                                <li>sda</li>
                            </ul>
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
        background-color: lightgray;
        text-align: left;

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
                        }
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