<template>
  <header class="header">
    <div class="header__container">
      <img
        class="header__container-logo"
        src="../../assets/imgs/svg/logo.svg"
      />
      <img
        class="header__container-nav"
        src="../../assets/imgs/svg/navigation.svg"
      />
    </div>
  </header>
</template>
<style lang="stylus" scoped>
.header
  width 100%
  position absolute
  height 35vw
  display flex
  justify-content center

  .header__container
    width 65%
    display flex
    justify-content space-between

    .header__container-logo
      width 35%

    .header__container-nav
      width 8%
</style>
