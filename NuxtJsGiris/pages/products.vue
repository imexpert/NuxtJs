<template>
    <div>
        <div class="input-container">
            <input type="text" v-model="productId" />
            <button class="button--green" @click="showProduct">Ürünü Göster</button>
        </div>
        <nuxt-child ></nuxt-child>
    </div>
</template>

<script>
    export default {
        validate(arg){
            console.log(arg);
            return /^\d+$/.test(arg.params.productId);
        },
    data() {
        return {
        productId: null
        };
    },
    methods: {
        showProduct() {
        this.$router.push("/products/" + this.productId);
        }
    }
    };
</script>