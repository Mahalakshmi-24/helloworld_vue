<template>
<header>
  <h1>{{props.title}}</h1>
<p>This is header of the page</p>

</header>
</template>
<script setup>
import {defineProps} from 'vue';
const props = defineProps({

  title : {
    type: String,
    default: 'default text'
  }

});

</script>