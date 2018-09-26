<template>
  <div>
    <h1>Welcome</h1>
    <h2>What's up</h2>
  </div>
</template>

<script>
import sourceData from '@/data'
console.log(sourceData)
export default {
  name: 'HelloWorld',
  data () {
    return {
      threads: sourceData.threads,
      posts: sourceData.posts,
      users: sourceData.users
    }
  }
}
</script>
