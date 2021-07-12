<script>
import {
  RepeatIcon,
  UsersIcon,
  PieChartIcon,
  CheckCircleIcon,
  ChevronsRightIcon
} from 'vue-feather-icons'

export default {
  components: {
    RepeatIcon,
    UsersIcon,
    PieChartIcon,
    CheckCircleIcon,
    ChevronsRightIcon
  }
}
</script>

<template>
  <div class="space-y-32">
    <div class="offer">
      <RepeatIcon />
      <UsersIcon />
      <PieChartIcon />
      <CheckCircleIcon />
      <ChevronsRightIcon />
      Toto
    </div>
  </div>
</template>

<style>
.offer {
  background: gray;
}
</style>
