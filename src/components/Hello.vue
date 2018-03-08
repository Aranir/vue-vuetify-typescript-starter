
<template>
    <div>
        <div class="greeting">Hello {{name}}{{exclamationMarks}}</div>
        <v-btn color="success">Success</v-btn>
        <div class="text-xs-center">
          <v-chip>Example Chip</v-chip>
        </div>
    </div>
</template>

<script lang="ts">
import Vue from "vue";
export default Vue.extend({
  props: {
    name: String
  },
});
</script>
