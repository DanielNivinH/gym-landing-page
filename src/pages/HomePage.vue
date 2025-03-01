<template>
  <main class="main">
    <section class="main__home">
      <div class="main__home-content">
        <h1 class="main__home-content-title">
          Free trial session with a trainer
        </h1>
        <button class="main__home-content-button">Detailed</button>
      </div>
    </section>
    <section class="main__advantages">
      <h2 class="main__advantages-title">Reasons to join</h2>
      <div class="main__advantages-list">
        <div class="main__advantages-item">
          <img
            class="main__advantages-item-icon"
            src="../assets/imgs/svg/advantages/first-icon.svg"
          />
          <div class="main__advantages-item-text">
            <h3 class="main__advantages-item-text-title">15000 sq.m.</h3>
            <div class="main__advantages-item-text-description">
              A spacious gym for sport - a safe distance between exercise
              machines
            </div>
          </div>
        </div>
        <div class="main__advantages-item">
          <img
            class="main__advantages-item-icon"
            src="../assets/imgs/svg/advantages/second-icon.svg"
          />
          <div class="main__advantages-item-text">
            <h3 class="main__advantages-item-text-title">
              More than 200 equipment
            </h3>
            <div class="main__advantages-item-text-description">
              No queues aat the simulators, Premium equipment from LifeStyle,
              Hammer Strength, TechnoGym.
            </div>
          </div>
        </div>
        <div class="main__advantages-item">
          <img
            class="main__advantages-item-icon"
            src="../assets/imgs/svg/advantages/third-icon.svg"
          />
          <div class="main__advantages-item-text">
            <h3 class="main__advantages-item-text-title">4 fitness zones</h3>
            <div class="main__advantages-item-text-description">
              From cardio to funtional and cycle. Separate area for boxing and
              mixed martial arts
            </div>
          </div>
        </div>
        <div class="main__advantages-item">
          <img
            class="main__advantages-item-icon"
            src="../assets/imgs/svg/advantages/fourth-icon.svg"
          />
          <div class="main__advantages-item-text">
            <h3 class="main__advantages-item-text-title">
              Round-the-clock-operation
            </h3>
            <div class="main__advantages-item-text-description">
              The Gym is open 24 hours a day, also works on all holidays and
              weekends
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>
<style lang="stylus" scoped>
.main
  padding 18% 0 0 0

  .main__home
    padding 25% 0 0 0
    display flex
    justify-content center
    background linear-gradient(290deg, transparent, black 70%), linear-gradient(180deg,transparent, transparent, black 95%), url('../assets/imgs/jpg/home/home-sm.jpg')
    background-repeat no-repeat
    background-size auto 120%
    background-position  right top

    .main__home-content
      width 65%
      display flex
      flex-direction column
      align-items center

      .main__home-content-title
        padding 8% 0 0 0
        text-align center
        font-size 2rem

      .main__home-content-button
        margin 25% 0 0 0
        width 50%
        height 40px
        color #000
        font-weight bold
        background-color #FAFF00
        border-radius 30px

  .main__advantages
    padding 25% 0 25% 0
    display flex
    justify-content center
    flex-direction column
    align-items center

    .main__advantages-title
      padding 8% 0 0 0
      text-align center
      font-weight bold
      font-size 1.5rem

    .main__advantages-list
      display grid
      grid-template-columns 1fr
      width 70%
      padding 8% 0 0 0

      .main__advantages-item
        display flex

        .main__advantages-item-icon
          padding 0 10% 0 0
          width 35px

        .main__advantages-item-text

          .main__advantages-item-text-title
            padding 10% 0 0 0
            font-weight bold
            font-size 1rem
</style>
