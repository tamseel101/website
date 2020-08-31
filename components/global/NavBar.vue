<template>
  <div class="nav g-header p-3">
    <div class="nav-header">
      <nuxt-link
        class="d-flex align-items-center ml-1"
        to="/"
      >
        <img
          class="logo"
          src="../../static/logos/cssc.png"
        />
        <span class="logo-text">UTM CSSC</span>
      </nuxt-link>
    </div>
    <div class="nav-links">
      <nuxt-link
        to="/resources"
        class="g-nav-link mr-4"
      >Resources
      </nuxt-link>
      <nuxt-link
        to="/ask-an-exec"
        class="g-nav-link mr-4"
      >Ask an Exec
      </nuxt-link>
      <nuxt-link
        to="/tech-of-the-month"
        class="g-nav-link mr-4"
      >Tech of the month
      </nuxt-link>
      <a
        target="_blank"
        href="https://www.github.com/utm-cssc"
        class="g-nav-link mr-4"
      >Github</a>
    </div>
  </div>
</template>

<style scoped>
  .g-header {
    height: 8vh;
  }

  .logo {
    height: 48px;
    width: 48px;
    margin-right: 16px;
  }

  .logo-text {
    font-size: 26px;
    color: var(--color-text);
    font-weight: 500;
    text-transform: uppercase;
  }

  .nav > .nav-links {
    float: right;
    display: flex;
    margin-left: auto;
    font-size: 20px;
  }

  .nav > .nav-header {
    display: inline-block;
    text-decoration: none;
  }

</style>
<style>
  .nav {
    width: 100%;
    position: relative;
    border-bottom: 1px solid rgba(232, 231, 231, 0.97);
  }
</style>
