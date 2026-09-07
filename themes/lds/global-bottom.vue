<template>
  <footer class="slide-number">
    {{ $nav.currentPage }} / {{ $nav.total }}
  </footer>
</template>

<style>
.slide-number {
  position: absolute;
  right: 30px;
  bottom: 20px;

  background-color: #003059;
  color: white;

  padding: 4px 10px;
  border-radius: 4px;

  font-size: 16px;
  font-weight: 600;

  z-index: 100;
}

#slide-content:has(#slideshow .slidev-page:not([style*='display: none']) .slidev-layout.cover) .slide-number {
  display: none;
}
</style>