<template>
  <footer class="page-footer teal">
    <div class="container">
      <slot name="main"></slot>
    </div>
    <div class="footer-copyright">
      <div class="container">
          <slot name="copyright"></slot> 
      </div>
    </div>
  </footer>
</template>

<script>
export default {
    name: "Footer"
}
</script>

