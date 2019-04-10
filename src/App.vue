<template>
  <v-app>
    <div class="center">
      <LegoBoard />
    </div>
  </v-app>
</template>

<script>
import LegoBoard from './components/LegoBoard'

export default {
  name: 'App',
  components: {
    LegoBoard
  },
  data () {
    return {
      //
    }
  }
}
</script>

<style>
.center {
  display: flex;
  justify-content: center;
  margin-top: 50px;
}
</style>
