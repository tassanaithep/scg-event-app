<template>
  <div>
    <h1>Event Show # {{id}}</h1>
  </div>
</template>
<script>
export default {
  props: {
    id: {
      type: Number,
      required: true
    }
  }
};
</script>