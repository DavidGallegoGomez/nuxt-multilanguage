<template>
  <header class="top-header util__flex util__container">
    <nav class="top-header__col">
      <li>
        <nuxt-link class="nav__item" to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link class="nav__item" to="/en/blog">Blog</nuxt-link>
      </li>
    </nav>
    <a href="/" class="top-header__col top-header__logo">
      <img
        src="//a.storyblok.com/f/42016/1096x313/0353bf6654/logo2.png"
        alt="Logo"
      />
    </a>
    <nav class="top-header__col top-header__second-navi">
      <ul class="nav">
        <li>
          <nuxt-link class="nav__item" to="/en/blog">English</nuxt-link>
        </li>
        <li>
          <nuxt-link class="nav__item" to="/de/blog">German</nuxt-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style lang="scss">
.top-header {
  justify-content: space-between;
  padding: 30px 0;
}
.top-header__logo {
  text-align: center;
  position: absolute;
  left: 50%;
  img {
    position: relative;
    max-height: 60px;
    left: -50%;
    top: -15px;
  }
}
.top-header__second-navi {
  text-align: right;
}
</style>
