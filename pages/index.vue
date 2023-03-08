<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/">Crash Dojo</NuxtLink>
        <ul>
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/products">Products</NuxtLink></li>
        </ul>
        <a href="/about">normal link -- about page</a>
      </nav>
    </header>
    <h2>Home</h2>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Molestiae saepe
      sint molestias reprehenderit non eaque fugiat libero. Corporis, provident
      iusto?
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae
      doloremque commodi fugit! Iusto totam itaque deserunt animi commodi ipsa
      eligendi.
    </p>
  </div>
</template>

<script setup></script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p {
  margin: 20px 0;
}
</style>
