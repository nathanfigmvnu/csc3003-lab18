<template>
  <div class="board">
  </div>
</template>

<script>

export default {
  name: "LegoBoard",
  components: {
  },
  props: {

  },
  data: function() {
    return {

    }
  },
  methods: {
    
  }
}
</script>

<style scoped>
.board {
  border: 1px solid;
  width: 600px;
  height: 600px;
  background-color: #191;
  display: flex;
  justify-content: space-around;
  flex-direction: row;
  align-items: center;
}
</style>
