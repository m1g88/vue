
<template>  
  <div>
    <input v-model="name">
    <hello-component v-bind:name="name"></hello-component>
  </div>
</template>

<script>
import HelloComponent from './components/Hello'

export default {
  components: {
    HelloComponent
  },
  data () {
    return {
      name: '',
      list: [
        1, 2, 3, 4
      ]
    }
  },
  methods: {
    sayHello () {
      window.alert('Hi, ' + this.name)
    }
  }
}
</script>