<template>
  <div :class="$style.vueName"></div>
</template>
<script>
export default {
  name: 'vueName',
  mixins: [],
  components: {},
  props: {
  },
  data () {
    return {
    }
  },
  computed: {
  },
  watch: {
  },
  created () {
    console.log('初始化好了')
    console.log(123)
  },
  mounted () {
  },
  methods: {
  },
  beforeDestroy () {
  }
}
</script>
<style module lang="scss">
.vueName {
  :global {
  }
}
</style>
