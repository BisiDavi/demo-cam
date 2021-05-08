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
        <p class="has-text-centered my-2">
          *All featres are free for our user. You will need to be logged to use
          our cam site.
        </p>
        <p class="has-text-centered my-2">Don’t have account?</p>
        <b-button type="is-text" class="button is-centered is-flex"
          >Create it now!</b-button
        >
      </div>
    </section>
    <div class="bubble-right">
      <img src="/bubble2.png" />
    </div>
  </div>
</template>
<style lang="css" scoped>
.container {
  background-color: #cde7fd;
  height: 100vh;
  position: relative;
}
.button {
  margin: auto;
}
.bubble-left {
  position: absolute;
  top: 0;
  left: 0;
}
.hero {
  z-index: 1;
  position: relative;
}
.bubble-right {
  position: absolute;
  top: 150px;
  right: 30px;
}
.title {
  font-family: Montserrat;
  font-style: normal;
  font-weight: 800;
  font-size: 64px;
  line-height: 78px;
  /* identical to box height */
  letter-spacing: 0.07em;
  color: #ff1a1a;
}
</style>
