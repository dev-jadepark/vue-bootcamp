<template>
  <div>
    <div>
      <input type="checkbox" name="" id="html" value="HTML" v-model="favoriteLang" />
      <label for="html">HTML</label>
    </div>
    <div>
      <input type="checkbox" name="" id="css" value="CSS" v-model="favoriteLang" />
      <label for="css">CSS</label>
    </div>
    <div>
      <input type="checkbox" name="" id="js" value="JS" v-model="favoriteLang" />
      <label for="js">JS</label>
    </div>
    <div>선택한 언어:{{favoriteLang}}</div>
    <!-- checkbox의 경우 v-model로 연결해주면 value값과 양방향 바인딩이 되는 것이 아니라 checked 된 value를 배열에 넣는 원리이므로 input과 select와는 조금 다르다 -->
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      favoriteLang: ['JS']
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
