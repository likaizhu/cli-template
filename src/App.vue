<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from '@/components/helloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
  data () {
    return {
      pass: '111',
      arr: [1, 2, 3],
      obj: {
        name: '1',
        age: 1,
      },
      c: { a: 1 },
    }
  },
  mounted () {
    // const name = this.pass
    // this.getPass(name)
  },
  methods: {
    // getPass(name) {
    //   let pass = 2
    //   let res = 3
    //   if (a === pass) {
    //     res = 2
    //   }
    //   const c = 12
    //   c = 0
    //   pass = this.pass + a
    //   res = 1 + 2
    //   console.log(pass)
    //   console.log(name)
    //   console.log(res)
    // },
    // he() {},
  },
}
</script>

<style lang="less" src="./style/index.less"></style>
