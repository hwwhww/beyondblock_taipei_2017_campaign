<template>
  <section class="contact contact__bg">
    <div class="contact__box">
      <div class="contact__icon">
        <a href="https://www.facebook.com/eth.taipei/" target="_blank"><i class="fa fa-facebook icon" aria-hidden="true"></i></a>
      </div>
      <div class="contact__icon">
        <a href="https://www.meetup.com/Taipei-Ethereum-Meetup/" target="_blank"><i class="fa fa-slack icon" aria-hidden="true"></i></a>
      </div>
      <div class="contact__icon">
        <a href="https://github.com/EtherTW" target="_blank"><i class="fa fa-github icon" aria-hidden="true"></i></a>
      </div>
    </div>
    <div class="contact__organizer">
      <span>2017 © Taipei Ethereum Meetup</span>
    </div>
  </section>
</template>

<script>
export default {
  name: 'contact'
}
</script>

<style scoped lang="scss">
.fa {
  color: #FFF;
}

.contact {
  width: 100%;
  &__bg {
    height: 120px;
    width: 100%;
    background-image: linear-gradient(-90deg, #37ECBA 0%, #72AFD3 100%);
  }
  &__icon {
    margin: 0px 24px;
    margin-top: 26px; 
    margin-bottom: 10px;
    border-radius: 50%;
    display: inline-block;
    text-align: center;
    width: 135px;
    line-height: 50px;
    font-size: 40px;
    color: #FFF;
    cursor: pointer;
  }
  &__box {
    margin: 0 auto;
    width: 560px;
  }
  &__organizer {
    display: block;
    margin: 0 auto;
    width: 560px;
    text-align: center;
  }
  &__organizer span {
    display: block;
    font-family: NotoSansCJKtc-Regular;
    font-size: 10px;
    color: #FFF;
    letter-spacing: 0.56px;
  }
}

@media only screen and (max-width: 767px) {
  .staff__box {
    padding: 10px;
  }
}

@media only screen and (max-width: 575px) {
  .contact__box {
    width: 375px;
    padding-top: 20px;
    margin-bottom: 10px;
  }
  .contact__icon {
    margin: 0 auto;
    margin: 0px 10px;
    width: 100px;
  }
  .contact__organizer {
    display: block;
    margin: 0 auto;
    width: 375px;
    text-align: center;
  }
}
</style>
