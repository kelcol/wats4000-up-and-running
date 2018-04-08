<template style>
  <div class="custom">    
      <input type="text" v-model="custom" placeholder="What's your name?" >
      <br />
      <h1 v-if="custom.length === 0">Markdown Editor</h1>
      <h1 v-else>{{custom}}'s Markdown Editor</h1>
  </div>
</template>

<script>
export default {  
  data() {
    return {
      custom: "",
    }
  },
}
</script>