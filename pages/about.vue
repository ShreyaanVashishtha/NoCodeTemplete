<template>
  <main>
    <h1>About</h1>
    <NuxtLink to="/about">
    <bold-text
     Killed by Google. There's a lot of them! By Shreyaan Vashishtha
    />
    </NuxtLink>
    <a href="https://nuxtjs.org">External Link to another page</a>
    
    <style lang="scss" scoped>
@import '../assets/style/variables';
@media (max-width: 1200px) {
    grid-template-columns: 1fr 1fr 1fr 1fr;
  }
  @media (max-width: 960px) {
    grid-template-columns: 1fr 1fr 1fr;
  }
  @media (max-width: 768px) {
    grid-template-columns: 1fr 1fr;
  }
  @media (max-width: 320px) {
    grid-template-columns: 1fr;
  }
}
</style>
  </main>
</template>
