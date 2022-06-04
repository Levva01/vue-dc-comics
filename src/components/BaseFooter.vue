<template>
  <footer class="footer">

    <nav class="footer__nav">

      <div>
        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        <span>DIGITAL COMICS</span>
      </div>
      
      <div>
        <img src="../assets/img/buy-comics-merchandise.png" alt="">
        <span>DC MERCHANDISE</span>
      </div>
      
      <div>
        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
        <span>SUBSCRIPTION</span>
      </div>
      
      <div>
        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
        <span>COMIC SHOP LOCATOR</span>
      </div>
      
      <div>
        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
        <span>DC POWER VISA</span>
      </div>

    </nav>

    <div class="footer__info">

      <div class="info-container">

        <ul>
          <h3>DC COMICS</h3>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
        </ul>

        <ul>
          <h3>SHOP</h3>
          <li>Shop DC</li>
          <li>Shop DC Collectibles</li>
        </ul>

        <ul>
          <h3>DC</h3>
          
          <li>Terms of Use</li>
          <li>Privacy policy (New)</li>
          <li>Ad Choises</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshops</li>
          <li>CPSC Certificates</li>
          <li>Ratings</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>

        <ul>
          <h3>SITES</h3>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>

      </div>

      
      <img src="../assets/img/dc-logo-bg.png" alt="">

    </div>

  </footer>
</template>

<script>
export default {
    name: 'BaseFooter',
    data() {

    }
}
</script>

<style lang="scss" scoped>

  .footer{
    
    //nav
    &__nav{
      height: 200px;
      width: 100%;
      display: flex;
      align-items: center;
      justify-content: space-evenly;
      background-color: #0282f9;
      color: white;

      div{
        display: flex;
        align-items: center;
        font-size: .75rem;
      }

      img{
        width: 30px;
        height: auto;
      }
    }
    // fine nav

    // footer info

    &__info{
      height: 500px;
      display: flex;
      justify-content: space-around;

      background-image: url("../assets/img/footer-bg.jpg");

      img{
        width: 500px;
        height: auto;
        z-index: 1;
      }

      .info-container{
        z-index: 2;
        margin: 30px 0;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;

        ul{

          margin-right: 2.5rem;
          margin-bottom: 1.25rem;

          h3{
            color: white;
            font-size: 1.875rem;
            margin-bottom: 10px;
          }

          li{
            margin-bottom: 0.5rem;
            color: gray;
            font-size: 1rem;
            list-style: none;
          }
        }
      }


    }

    // fine footer info




  }

</style>