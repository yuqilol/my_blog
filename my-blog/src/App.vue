<template>
  <div id="app">
    <!-- <add-blog></add-blog> -->
    <show-blogs></show-blogs>
  </div>
</template>

<script>
  // 112
// import HelloWorld from './components/HelloWorld'
import AddBlog from './components/addblog'
import ShowBlogs from './components/ShowBlogs'

export default {
  name: 'App',
  components: {
    AddBlog,
    ShowBlogs
  }
}
</script>

<style>

</style>
