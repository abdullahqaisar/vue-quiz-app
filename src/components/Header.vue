<template>
  <div>
    <b-nav tabs>
      <b-nav-item disabled><b>Vue Quiz App</b></b-nav-item>
      <b-nav-item disabled
        >Counter {{ correctAnswers }}/{{ totalAnswers }}</b-nav-item
      >
    </b-nav>
  </div>
</template>

<script>
export default {
  props: ["correctAnswers", "totalAnswers"],
};
</script>
