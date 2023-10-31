<template>
  <header id="headerType" class="header__wrap" :class="element">
    <div class="header__inner">
      <div class="header__logo">
        <a href="/">Web <em>site</em></a>
      </div>
      <div class="header__menu">
        <ul>
          <li><a href="/">헤더 영역</a></li>
          <li><a href="/">슬라이드 영역</a></li>
          <li><a href="/">배너 영역</a></li>
          <li><a href="/">컨텐츠 영역</a></li>
          <li><a href="/">푸터 영역</a></li>
        </ul>
      </div>
      <div class="header__member"><a href="#">로그인</a></div>
    </div>
  </header>
</template>

<script>
export default {
  props: {
    element: String,
  }
}
</script>