<script setup></script>

<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container">
      <a class="navbar-brand" href="#">Navbar</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <!-- 使用<NuxtLink/>切換頁面 -->
              <NuxtLink class="nav-link" to="/">首頁</NuxtLink>            
          </li>
          <li class="nav-item">
            <!-- 使用<NuxtLink/>切換頁面 -->
            <NuxtLink class="nav-link" to="/room">房型</NuxtLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <main class="container">
    <slot />
  </main>
</template>

<style scoped></style>
