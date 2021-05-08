<template>
  <div
    class="container is-fluid is-flex is-justify-content-center is-align-items-center"
  >
    <div class="bubble-left">
      <img src="/bubble1.png" />
    </div>
    <section class="hero is-centered">
      <div class="hero-body">
        <h1 class="has-text-centered title">MelodyCam</h1>
        <h3 class="has-text-centered my-2">
          Find new friends by video chatting with people from all over the
          world!
        </h3>
        <h5 class="has-text-centered my-2 text">
          *All features are free for our user. You will need to be logged to use
          our cam site.
        </h5>
        <Button text="Signup" class="my-5" />
        <p class="has-text-centered my-1 text">Don’t have account?</p>
        <b-button type="is-text" class="create is-centered is-flex"
          >Create it now!</b-button
        >
      </div>
    </section>
    <div class="bubble-right">
      <img src="/bubble2.png" />
    </div>
  </div>
</template>
<script>
import Button from '@/components/Button.vue'

export default {
  name: 'Homepage',
  components: {
    Button,
  },
}
</script>

<style lang="css" scoped>
.container {
  background-color: #cde7fd;
  height: 100vh;
  position: relative;
}
.create {
  margin: auto;
  color: #0e5979;
  font-size: 22px;
  line-height: 27px;
  text-decoration: none;
}
.bubble-left {
  position: absolute;
  top: 0;
  left: 0;
}
.hero {
  z-index: 1;
  position: relative;
  width: 50%;
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  width: 50%;
}
.hero-body h3 {
  font-weight: normal;
  font-size: 30px;
  line-height: 37px;
  text-align: center;
  color: #000000;
}
.hero-body h5 {
  letter-spacing: 0.045em;
  color: rgba(0, 0, 0, 0.5);
}
.text {
  font-style: normal;
  font-weight: normal;
  text-align: center;
  font-size: 22px;
  line-height: 27px;
  color: #000000;
}
.bubble-right {
  position: absolute;
  top: 150px;
  right: 30px;
}
.title {
  font-weight: 800;
  font-size: 64px;
  line-height: 78px;
  /* identical to box height */
  letter-spacing: 0.07em;
  color: #ff1a1a;
}
</style>
