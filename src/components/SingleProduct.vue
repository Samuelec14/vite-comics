<script>
export default {
    name: "SingleProduct",
    data() {
        return{

        };
    },
    props: {
        productThumb: String,
        productSeries: String
    }
}
</script>

<template>

    <div class="product">
        <div class="img-container">
            <img :src="productThumb" :alt="productSeries"/>
        </div>
        <h3>{{productSeries}}</h3>
        
    </div>

</template>

<style lang="scss" scoped>
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

</style>