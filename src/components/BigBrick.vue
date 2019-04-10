<template>
  <div class="bigbrick">
    <SmallBrick />
    <SmallBrick />
    <SmallBrick />
  </div>
</template>

<script>
import SmallBrick from './SmallBrick';

export default {
  name: "BigBrick",
  components: {
    SmallBrick
  }
}
</script>

<style scoped>
.bigbrick {
  border: 1px solid;
  width: 200px;
  height: 400px;
  background-color: #911;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
}
</style>
