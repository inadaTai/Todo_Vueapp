<template>
  <div>
    <ul id="dropdown" class="dropdown-content">
    <li><router-link to="/">Topページ</router-link></li>
    <li><router-link to="/about">アバウト</router-link></li>
    <li><router-link to="/contact">お問い合わせ</router-link></li>
    </ul>
    <nav>
      <div class="nav-wrapper container">
        <a href="/" class="brand-logo left">Todo 管理くん</a>
        <ul class="right hide-on-med-and-down">
          <li><router-link to="/">Topページ</router-link></li>
          <li><router-link to="/about">アバウト</router-link></li>
          <li><router-link to="/contact">お問い合わせ</router-link></li>
        </ul>
        <ul class="right hide-on-large-only">
          <li>
            <a class="dropdown-button" href="#!" data-activates="dropdown">
              メニュー<i class="material-icons right">arrow_drop_down</i>
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>
