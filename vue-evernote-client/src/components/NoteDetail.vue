<template>
  <div id="note-detail">
      <h1> {{msg}}: {{ $route.params.noteId }}</h1>
      <h1> {{msg}}: {{ $route.params.noteId }}</h1>
      <h2>hello world</h2>
  </div>
</template>

<script>
export default {
    name:'Login',
    data(){
        return {
            msg: '笔记本详情',
        }
    }
}
</script>

<style>
h1 {
    color: blue;
}
</style>