<template>
    <div v-if="event">
        <p>Register for event here</p>
    </div>
  </template>
  
<script>
export default {
    props: ['event'],
}
</script>