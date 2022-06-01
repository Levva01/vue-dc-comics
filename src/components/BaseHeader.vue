<template>
  <header class="header">

      <div class="header__logo">
          <img src="../assets/img/dc-logo.png" alt="">
      </div>

      <div class="header__nav">
          <ul>
              <li><a href="#">CHARACTERS</a></li>
              <li><a href="#">COMICS</a></li>
              <li><a href="#">MOVIES</a></li>
              <li><a href="#">TV</a></li>
              <li><a href="#">GAMES</a></li>
              <li><a href="#">COLLECTIBLES</a></li>
              <li><a href="#">VIDEOS</a></li>
              <li><a href="#">FANS</a></li>
              <li><a href="#">NEWS</a></li>
              <li><a href="#">SHOP</a></li>
          </ul>
      </div>

  </header>
</template>

<script>
export default {
    name: 'BaseHeader',
    data() {

    }
}
</script>

<style lang="scss" scoped>

.header{
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 120px;

    &__logo {
        img {
            width: 80px;
            height: auto;
        }
    }

    &__nav {
        ul{
            list-style: none;
            display: flex;
            justify-content: center;
            gap: .9375rem;
            font-size: .875rem;
            font-weight: bold;

            a{
                text-decoration: none;
                color: #464646;
            }
        }

    }


}

</style>