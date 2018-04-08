<template>
  <div class="custom">    
      <input type="text" v-model="custom" placeholder="What's your name?" >
      <!-- <button v-on:click="personalizeHeading(you)" v-on:keyup="pressKey">Submit</button> -->
      <br />
      <h1>{{custom}} Markdown Editor</h1>
  </div>
</template>


<script>
export default {
  name: 'custom',    
  data() {
    return {
      custom: "",
    }
  },
  methods: {
    personalizeHeading: function(custom){
      console.log(custom);      
  },
  // This doesn't work
  pressKey: function(custom) {
    return custom + "'s";
      }
}
}
</script>
