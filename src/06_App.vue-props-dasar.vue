<template>

<div> komponent induk</div>
<hr>
  <anak text="Text Dari induk"></anak>
  <anak :text="message"></anak>
<hr>
  <child-component :text1="message"></child-component>
<hr>

</template>

<script>
import Anak from "./components/Anak.vue"
import ChildComponent from "./components/ChildComponent.vue"


export default {
    components: { Anak, ChildComponent },
    data () {
      return {
          message: 'Halo bro'
      }
    }
}

</script>
