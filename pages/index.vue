<template>
  <Html :lang="dynamic > 50 ? 'ar-EG' : 'en-US'">
    <Head>
      <Title>Restaurantly</Title>
      <Meta name="description" content="My page is cool" />
      <Link
        rel="preload"
        href="https://www.iconpacks.net/icons/2/free-sad-face-icon-2691-thumb.png"
        as="script"
      />
    </Head>
  </Html>
  <div class="container">
    <h1>Welcome To Restaurantly</h1>
    <nuxt-link to="/resraurants">Go To Resraurants</nuxt-link>
  </div>
</template>
<style lang="scss" scoped>
.container {
  text-align: center;
  padding-top: 100px;
}
</style>
