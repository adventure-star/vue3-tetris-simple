<template>
  <BoardGameGrid :grid="nextPiece" />
</template>

<script>
import BoardGameGrid from "./BoardGameGrid.vue";

export default {
  props: {
    nextPiece: {
      type: Array,
      required: true,
    },
  },

  components: {
    BoardGameGrid,
  },
};
</script>
