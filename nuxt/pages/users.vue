<template>
  <div>
    <input type="text" v-model="userId">
    <button @click="onLoadUser">Load User</button>
    <nuxt-child/>
  </div>
</template>

<script>
export default {
  layout: 'users',
  data() {
    return {
      userId:''
    }
  },
  methods: {
    onLoadUser(){
      this.$router.push('/users/'+this.userId)
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
