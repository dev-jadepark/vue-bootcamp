<template>
  <!-- vue의 장점은 html, js, css를 모두 분리하여 작성할 수 있다. -->
  <!-- vue에서는 최상위 태그로 항상 묶어주어야 한다. -->
  <div>
    <h1>Hello {{ username }}!!!</h1>
    <p>{{message}}</p>
  </div>
</template>
<script>
export default {
  data() {
    return {
      username: 'Jade Park',
      message: 'Welcome 개발자의 품격',
      arr: [],
      obj: {}
    }
  }
}

</script>
