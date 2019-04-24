<template>
  <div class="footer container-fluid">
    Copyright {{years}} by Than Do.
    <!-- Copyright 2019-{{new Date().getFullYear()}} by Than Do. -->
    <!-- <br> -->
    All Rights Reserved.
  </div>
</template>

<script>
export default {
    computed: {
        years() {
            const originalYear = 2019
            const currentYear = new Date().getFullYear()
            let years = originalYear
            if(currentYear !== originalYear) {
                years = originalYear + '-' + currentYear
            }
            return years
        }
    }
}
</script>

<style scoped>
.footer {
  position: fixed;
  right: 0;
  bottom: 0;
  left: 0;
  padding: 1rem;
  background-color: #17a2b8 !important;
  color: #fff;
  text-align: center;
}
</style>
