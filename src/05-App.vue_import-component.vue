<template>

<div> komponent induk</div>
<hr>
  <anak></anak>
<hr>
  <child-component></child-component>
<hr>

</template>

<script>
import Anak from "./components/Anak.vue"
import ChildComponent from "./components/ChildComponent.vue"


export default {
    components: { Anak, ChildComponent }
}

</script>
