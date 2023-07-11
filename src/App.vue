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
  <h1>HTML Classes Binding:-</h1>
  <Ex04BindingClasses />
  <hr />
  <h1>HTML Inline style Binding:-</h1>
  <Ex05BindingStyles />
  <hr />
  <h1>ConditionalRendering:-</h1>
  <Ex01ConRenIfElse />
  <hr />
  <h1>ConditionalRendering:-</h1>
  <Ex02ConRenVShow />
  <hr />
</template>

<script>
import Ex01BindingText from "./components/01Binding/Ex01BindingText.vue";
import Ex02BindingHTML from "./components/01Binding/Ex02BindingHTML.vue";
import Ex03BindingAttributes from "./components/01Binding/Ex03BindingAttributes.vue";
import Ex04BindingClasses from "./components/01Binding/Ex04BindingClasses.vue";
import Ex05BindingStyles from "./components/01Binding/Ex05BindingStyles.vue";
import Ex01ConRenIfElse from "./components/02ConditionalRendering/Ex01ConRenIfElse.vue"
import Ex02ConRenVShow from "./components/02ConditionalRendering/Ex02ConRenVShow.vue"

export default {
  name: "App",
  components: {
    Ex01BindingText: Ex01BindingText,
    Ex02BindingHTML: Ex02BindingHTML,
    Ex03BindingAttributes: Ex03BindingAttributes,
    Ex04BindingClasses: Ex04BindingClasses,
    Ex05BindingStyles: Ex05BindingStyles,
    Ex01ConRenIfElse: Ex01ConRenIfElse,
    Ex02ConRenVShow: Ex02ConRenVShow,
  },
};
</script>