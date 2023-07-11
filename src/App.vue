<template>
  <h1>Text Binding:-</h1>
  <Ex01BindingText />
  <hr />
  <h1>HTML Binding:-</h1>
  <Ex02BindingHTML />
  <hr />
  <h1>HTML Attributes Binding:-</h1>
  <Ex03BindingAttributes />
  <hr />
</template>

<script>
import Ex01BindingText from "./components/01Binding/Ex01BindingText.vue";
import Ex02BindingHTML from "./components/01Binding/Ex02BindingHTML.vue";
import Ex03BindingAttributes from "./components/01Binding/Ex03BindingAttributes.vue";
export default {
  name: "App",
  components: {
    Ex01BindingText: Ex01BindingText,
    Ex02BindingHTML: Ex02BindingHTML,
    Ex03BindingAttributes: Ex03BindingAttributes,
  },
};
</script>