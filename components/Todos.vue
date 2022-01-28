<!-- Please remove this file from your project -->
<template>
  <div>
      <h1> This is Todo Mulder </h1>
      <h1> This is Todo Mulder </h1>
      <div> {{ data }} </div>
      <div>
        <a class="btn btn-primary" @click="sendOne()">Send</a>
      </div>
  </div>
</template>

<script>
export default {
  name: 'MulderTodos',
  props:["data"],
  created() {
    console.log('todo - created')
  },
  methods: {
    sendOne() {
      console.log('toto - click - sendOne')
    },
  }
  
}
</script>
