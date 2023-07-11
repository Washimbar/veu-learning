<template>
  <div>
    <!-- Simply class add -->
    <h2 class="underline">Heading 2 </h2>
    <!-- Dynamically added class -->
    <h4 class="underline" v-bind:class="status">Statues</h4>
    <!-- Class added with condition -->
    <h4  v-bind:class="isPromoted && 'promoted'">Statues</h4>
    <!-- Class added with ternary condition -->
    <h4  v-bind:class="isSoldOut ? 'booked' : 'new'">Ticket</h4>
    <!-- Class bind using array -->
    <h2 v-bind:class="['new','promoted']">Newly Promoted movie</h2>
    <!-- Class added using array with ternary condition -->
    <h2 v-bind:class="[isSoldOut ? 'booked' : 'new','promoted']">Newly Promoted movie</h2>
    <!-- Class added using object -->
    <h2 v-bind:class="{
      promoted: isPromoted, 
      booked: isSoldOut,
      'sold-out': isSoldOut,
    }">Review of Movie is 7.5</h2>

  </div>
</template>

<script>
export default {
  data() {
    return {
        status: 'success',
        isPromoted: true,
        isSoldOut: true,
    };
  },
};
</script>

<style>
    .underline {
        text-decoration: underline;
    }
    .promoted {
      color: green;
    }
    .new {
      color: powderblue;
    }
    .booked{
      color: yellowgreen;
    }
</style>