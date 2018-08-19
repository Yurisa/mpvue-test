<template>
  <div>

  </div>
</template>

<script>
import { get } from '@/util'
export default {
  async created () {
    console.log('小程序启动了')
    const res = await get('/weapp/test')
    console.log(res)
  }
}
</script>

<style scoped>

</style>
