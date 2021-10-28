<template>
  <div>
    <Header />
    <p>ボタンを押してね</p>
  </div>
</template>

<script>
import Header from '~/components/Header.vue'
export default{
  layout: 'users',
  components:{
    Header
  }
}
</script>
