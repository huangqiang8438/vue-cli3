<template>
  <div class="panel">
      {{txt}}
  </div>
</template>

<script>
export default {
  name: 'cmsPanel',
  data () {
    return {
      txt: '面板组件'
    }
  }
}
</script>

 <style lang="scss" scoped>
  .panel{
   width: 100px;
   height: 200px;
   background: red;
  }
</style>
