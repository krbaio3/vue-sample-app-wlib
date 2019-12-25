<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <DummyButton/>
  </div>
</template>

<script>
// @ is an alias to /src
import DummyButton from 'dummyButton';
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'home',
  components: {
    HelloWorld,
    DummyButton,
  },
};
</script>
