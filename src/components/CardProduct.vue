<template>
  <div class="product">
    <img :src="image" :alt="title">
    <h3>{{title}}</h3>
  </div>
</template>

<script>
export default {
    name: 'CardProduct',
    props: {
        title: String,
        image: {
            type: String,
            default: 'https://www.fidoo.com/wp-content/uploads/2020/02/placeholder.png'
        },
    }
}
</script>

<style lang="scss" scoped>
.product {
    padding: 15px;
    width: 12.5rem;
    margin: 0;

    h3{
        margin-top: .3125rem;
    }
}
</style>