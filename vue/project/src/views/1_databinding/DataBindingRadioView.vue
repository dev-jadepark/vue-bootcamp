<template>
  <div>
    <div>
      <input type="radio" name="" id="html" value="HTML" v-model="favoriteLang" />
      <label for="html">HTML</label>
    </div>
    <div>
      <input type="radio" name="" id="css" value="CSS" v-model="favoriteLang" />
      <label for="css">CSS</label>
    </div>
    <div>
      <input type="radio" name="" id="js" value="JS" v-model="favoriteLang" />
      <label for="js">JS</label>
    </div>
    <div>선택한 언어:{{favoriteLang}}</div>
    <!-- checkbox는 배열형 radio는 문자열로 선언해야 한다. -->
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      favoriteLang: 'JS'
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {
    myFunction() {
      console.log(this.userId)
    },
    changeData() {
      this.userId = 'jeremy'
    }
  }
}

</script>

<style>

</style>
