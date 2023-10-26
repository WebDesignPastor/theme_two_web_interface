<template>
  <UserProfile msg="Welcome to Your Vue.js App"/>
  <WorkingTime/>
  <WorkingTimes/>
  <ChartManager/>
  <ClockManager/>

</template>

<script>
import ChartManager from './components/ChartManager.vue';
import ClockManager from './components/ClockManager.vue';
import UserProfile from './components/UserProfile.vue';
import WorkingTime from './components/WorkingTime.vue';
import WorkingTimes from './components/WorkingTimes.vue';

export default {
  name: 'App',
  components: {
    UserProfile,
    WorkingTime,
    WorkingTimes,
    ChartManager,
    ClockManager
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
