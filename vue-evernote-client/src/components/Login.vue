<template>
<div class="login">
    <h1>{{ msg }}</h1>
</div>
  
</template>

<script>
export default {
    name: 'Login',
    data() {
        return {
            msg: 'This is login page'
        }
    }

}
</script>

<style>
h1 {
    color: red;
}
</style>