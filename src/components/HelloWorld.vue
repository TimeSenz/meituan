<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div v-html="msg1" />
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data(){
    return{
        msg1:'<span style="color:blue">Hello World</span>'
    }
  }
}
</script>
