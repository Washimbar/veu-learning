<template>
  <h1>Text Binding:-</h1>
  <Ex01BindingText />
  <hr>
  <h1>HTML Binding:-</h1>
  <Ex02BindingHTML />
  <hr>
</template>

<script>
import Ex01BindingText from  './components/Ex01BindingText.vue'
import Ex02BindingHTML from  './components/Ex02BindingHTML.vue'
export default{
  name: "App",
  components:{
    Ex01BindingText: Ex01BindingText,
    Ex02BindingHTML: Ex02BindingHTML

  },
  
}
</script>