<template>
  <div class="home">
    <img alt="Vue logo" width="280" src="../assets/fcc_secondary_small.png" />
    <HelloWorld msg="JavaScript Study Group (Retrospective)" />    
    <!-- Use the Component -->
    <Gist />
  </div> 
  
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import Gist from '../components/Gist.vue' // Import the Component

export default {
  name: "Home",
  components: {
    HelloWorld,
    Gist // Register the Component
  },
};

</script>
