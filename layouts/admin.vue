<template>
<div>
  <nav>
    <nuxt-link to="/">홈</nuxt-link>
    <nuxt-link to="/signup">회.가</nuxt-link>
    <nuxt-link to="/profile">프로필</nuxt-link>
    <nuxt-link to="/profile">admin</nuxt-link>
  </nav>
  <Nuxt />
  </div>
</template>

<script>
export default {
  name: 'DefaultLayout',
};
</script>
