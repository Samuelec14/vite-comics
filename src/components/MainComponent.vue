<script>
export default {
    name: "MainComponent",
    data() {
    return{
        products: [
    {
        "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
        "price": "$19.99",
        "series": "Action Comics",
        "type": "comic book"
    },
    {
        "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
        "price": "$3.99",
        "series": "American Vampire 1976",
        "type": "comic book"
    },
    {
        "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
        "price": "$16.99",
        "series": "Aquaman",
        "type": "graphic novel"
    },
    {
        "thumb": "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
        "price": "$2.99",
        "series": "Batgirl",
        "type": "comic book"
    },
    {
        "thumb": "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
        "price": "$3.99",
        "series": "Batman",
        "type": "comic book"
    },
    {
        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/50/Batman_Beyond_v.1_1.jpg",
        "price": "$2.99",
        "series": "Batman Beyond",
        "type": "comic book"
    },
    {
        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/0/0d/Batman_Superman_Vol_1_1.jpg",
        "price": "$3.99",
        "series": "Batman/Superman",
        "type": "comic book"
    },
    {
        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/cf/Batman_Superman_Annual_Vol_2_1.jpg",
        "price": "$4.99",
        "series": "Batman/Superman Annual",
        "type": "comic book"
    },
    {
        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/54/Batman_The_Joker_War_Zone_Vol_1_1.jpg",
        "price": "$5.99",
        "series": "Batman: The Joker War Zone",
        "type": "comic book"
    },
    {
        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/6/64/Batman_Three_Jokers_Collected.jpg",
        "price": "$6.99",
        "series": "Batman: Three Jokers",
        "type": "comic book"
    },
    {
        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/f/f8/Batman_White_Knight_Presents_Harley_Quinn_Vol_1_1.jpg",
        "price": "$4.99",
        "series": "Batman: White Knight Presents: Harley Quinn",
        "type": "comic book"
    },
    {
        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/c8/Catwoman_Vol_2_1.jpg",
        "price": "$16.99",
        "series": "Catwoman",
        "type": "graphic novel"
    }
]
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
                    <H2>CURRENT SERIES</H2>

                    <div class="products">
                        <div class="product" v-for="(product, productIndex) in products" :key="productIndex">
                            <div class="img-container">
                                <img :src="product.thumb" :alt="product.series">
                            </div>
                            <h3>{{product.series}}</h3>
                            
                        </div>
                        
                    </div>
                    

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
            min-height: 130px;
            // line-height: 120px;
            background-color: rgb(28, 28, 28);
            color: white;

            
            .container{
                position: relative;

                
                h2{
                    text-transform: uppercase;
                    position: absolute;
                    left: 0;
                    top: -20px;
                    background-color: rgb(2, 130, 249);
                    line-height: 0;
                    padding: 20px 14px;
                }
                .products{
                    display: flex;
                    flex-wrap: wrap;
                    padding: 40px 17px 0 17px;

                    .product{
                        min-height: 50px;
                        width: calc(100% / 6);
                        padding: 15px;
                        
                        
                        .img-container{
                            width: 100%;
                            height: 213px;

                            img{
                                height: 100%;
                            }
                        }

                        h3{
                            text-align: left;
                            padding-top: 20px;
                            text-transform: uppercase;
                            font-size: small;

                        }
                    }
                }
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