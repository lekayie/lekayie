<template>
  <vertical-timeline :inputData="mockedData" :reversed="false" />
</template>

<script>
import mock from "./mock.json";

export default {
  name: "Helloworld",
  data() {
    return {
      mockedData: mock
    };
  }
};
</script>

<style>
h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type:none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
