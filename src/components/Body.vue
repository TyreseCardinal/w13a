<template>
  <div class="body">
    <h2>About This Project</h2>
    <side-panel />
    <meet-the-developer />
    <meet-the-team />
  </div>
</template>

<script>
import SidePanel from './SidePanel.vue';
import MeetTheDeveloper from './MeetTheDeveloper.vue';
import MeetTheTeam from './MeetTheTeam.vue';

export default {
  components: {
    SidePanel,
    MeetTheDeveloper,
    MeetTheTeam
  }
}
</script>

<style scoped>
.body {
  padding: 20px;
  background-color: #C3E0E5;
}
</style>
