<template>
  <div id="tab-bar">
    <slot></slot>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
#tab-bar {
  display: flex;
  background: #f6f6f6;
  position: fixed;
  left: 0;
  bottom: 0;
  right: 0;
  box-shadow: 0 -1px 1px rgb(100, 100, 100, 0.1);
}
</style>