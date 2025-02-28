<template>
  <footer class="footer">
    <div class="footer__address">
      <h2 class="footer__address-title">Address</h2>
      <p class="footer__address-text">
        Republic of Belarus Minsk city Dzerzhinsky Avenue 15
      </p>
    </div>
    <div class="footer__contact">
      <h2 class="footer__contact-title">Contact</h2>
      <div class="footer__contact-item">
        <img
          class="footer__contact-item-icon"
          src="../../assets/imgs/svg/phone.svg"
        />
        <p class="footer__contact-item-text">+375(44)-777-24-12</p>
      </div>
      <div class="footer__contact-item">
        <img
          class="footer__contact-item-icon"
          src="../../assets/imgs/svg/mail.svg"
        />
        <p class="footer__contact-item-text">gym24@gmail.com</p>
      </div>
    </div>
    <div class="footer__social">
      <div class="footer__social-list">
        <img
          class="footer__social-item"
          src="../../assets/imgs/svg/socials/instagram.svg"
        />
        <img
          class="footer__social-item"
          src="../../assets/imgs/svg/socials/facebook.svg"
        />
        <img
          class="footer__social-item"
          src="../../assets/imgs/svg/socials/twitter.svg"
        />
        <img
          class="footer__social-item"
          src="../../assets/imgs/svg/socials/youtube.svg"
        />
      </div>
    </div>
  </footer>
</template>
<style lang="stylus" scoped>
.footer
  width 65%
  margin 0 auto

  .footer__address
    width 100%
    display flex
    flex-direction column
    align-items center

    .footer__address-title
      font-size 1.3rem
      padding 8% 0 8% 0

    .footer__address-text
      width 75%
      font-size 1rem
      text-align center

  .footer__contact
    padding 14% 0 0 0
    width 100%
    display flex
    flex-direction column
    justify-content center
    align-items center

    .footer__contact-title
      padding 0 0 8% 0

    .footer__contact-item
      display flex
      width 75%
      justify-content center

      .footer__contact-item-icon
        height 1.2rem
        width 1.2rem
        padding 0 5% 0 0

  .footer__social
    padding 8% 0 0 0

    .footer__social-list
      display flex
      justify-content space-between

      .footer__social-item
        height 1.4rem
        width 1.4rem
        padding 8px
        border 1px solid #fff
        border-radius 50px
</style>
