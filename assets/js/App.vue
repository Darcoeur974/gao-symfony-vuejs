<template>
    <div id="app">
        <hello></hello>
    </div>
</template>

<script>
import Hello from './components/Hello.vue'

class TestClassSyntax {}

export default {
  name: 'app',
  components: {
    Hello
  }
}
</script>
