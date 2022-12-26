<template>
  <div id="wrapper">
    <Sidebar/>
    <!-- Content Wrapper -->
    <div id="content-wrapper" class="d-flex flex-column">
        <!-- Main Content -->
        <div id="content">
          <Header/>
            <nuxt/>
        </div>
    </div>
  </div>
</template>

<script>
import Header from '@/components/layouts/Header.vue'
import Sidebar from '@/components/layouts/Sidebar.vue'
export default {
components : {
  Header,
  Sidebar
}
}
</script>

<style>

</style>