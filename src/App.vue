<template>
    <the-header title="RememberMe"></the-header>
    <the-resources></the-resources>
</template>

<script>
    // eslint-disable-next-line no-unused-vars
  import TheHeader from './components/layouts/TheHeader.vue';
  import TheResources from './components/learning-resource/TheResources.vue';
    export default{
        components: {
            TheHeader,
            TheResources
        },
        data(){
            return{
                
            }
        }
    }
</script>

<style>
* {
    box-sizing: border-box;
}

html {
    font-family: 'Roboto', sans-serif;
}

body {
    margin: 0;
}
</style>