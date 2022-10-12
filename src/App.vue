<template>
  <h1> HTML Is Fun</h1>
  <p> Just kidding, it's not really enjoyable at all. 
    But I'm making myself write in Vue anyways for learning.</p>
  <p> For now, I plan on just using raw HTML and CSS. 
    I will easily have the option to mess with javascript 
    whenever I want to, since it's right there.</p>
    <input type="text" v-model="egg" >
    <p>{{egg}}</p>
</template>
<script>
export default {
  components: {
  },
  props: [
  ],
  data () {
    return {
      egg:''
    }
  },
  mounted () {
  },
  created () {
  },
  computed: {
  },
  methods: {
  },
  watch: {
  }
}
</script>

<style>
</style>