<template>
  <div class="about">
    <CoreView/>
  </div>
</template>

<script>
export default {
  components: {
    // HelloWorld,
    CoreView: () => import('@/components/View')  
  },

  data: () => {

  },

  mounted() {},
}
</script>
