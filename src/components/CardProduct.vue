<template>
  <div class="product">
    <img :src="image" :alt="title">
    <h3>{{series}}</h3>
  </div>
</template>

<script>
export default {
    name: 'CardProduct',
    props: {
        series: String,
        image: {
            type: String,
            default: 'https://www.fidoo.com/wp-content/uploads/2020/02/placeholder.png'
        },
    }
}
</script>

<style lang="scss" scoped>
.product {
    background: #fff;
    padding: 15px;
    img {
        width: 100%;
    }
}
</style>