<template>
  <footer>
    <div class="container">
      <div class="primaColonna">
        <h4>DC COMICS</h4>
        <ul>
          <li>
            <a href="#">Characters</a>
          </li>
          <li>
            <a href="#">Comics</a>
          </li>
          <li>
            <a href="#">Movies</a>
          </li>
          <li>
            <a href="#">TV</a>
          </li>
          <li>
            <a href="#">Games</a>
          </li>
          <li>
            <a href="#">Videos</a>
          </li>
          <li>
            <a href="#">New</a>
          </li>
        </ul>
        <h4>SHOP</h4>
        <ul>
          <li>
            <a href="#">Shop DC</a>
          </li>
          <li>  
            <a href="#">Shop DC Collectibles</a>
          </li>
        </ul>
      </div>
      <div class="secondaColonna">
        <h4>DC</h4>
        <ul>
          <li>
            <a href="#">Terms of Use</a>
          </li>
          <li>
            <a href="#">Privacy policy(New)</a>
            </li>
            <li>
            <a href="#">Ad Choices</a>
            </li>
            <li>
            <a href="#">Advertising</a>
            </li>
            <li>
            <a href="#">Jobs</a>
            </li>
            <li>
            <a href="#">Subscriptions</a>
            </li>
            <li>
            <a href="#">Talent Workshops</a>
            </li>
            <li>
            <a href="#">CPSC Certificates</a>
            </li>
            <li>
            <a href="#">Ratings</a>
            </li>
            <li>
            <a href="#">Shop Help</a>
            </li>
            <li>
            <a href="#">Contact Us</a>
            </li>
            <li>
          </li>
        </ul>
      </div>
      <div class="terzaColonna">
        <h4>DC COMICS</h4>
        <ul>
          <li>
            <a href="#">DC</a>
          </li>
          <li>
            <a href="#">MAD Magazine</a>
          </li>
          <li>
            <a href="#">DC Kids</a>
          </li>
          <li>
            <a href="#">DC Universe</a>
          </li>
          <li>
            <a href="#">DC Power Visa</a>
          </li>
        </ul>
      </div>
      
      <img src="../../assets/img/dc-logo-bg.png">
    </div>
  </footer>
</template>

<script>
export default {
    name: 'FooterCentrale'
}
</script>

<style lang="scss" scoped>
footer {
  background-image: url('../../assets/img/footer-bg.jpg');
  background-position: center;
  height: 350px;
  overflow: hidden;
  margin: auto 0;

  h4 {
    color: #fff;
    margin: 30px 0 20px 0;
  }

  .primaColonna,
  .secondaColonna,
  .terzaColonna {
    float: left;
    margin-right: 20px;
  }

  ul {
    list-style-type: none;
    margin-bottom: 20px;
  }

  a {
    text-decoration: none;
    color: rgb(140, 140, 140);
    font-size: 10px;
  }

  img {
    float: right;
    transform: translateY(-15%);
  }
  
}
</style>