<template>
  <ul class="lang_con">
    <li
      v-for="language in languages"
      :key="language"
      class="lang_list"
      @click="handleCompleted(language)"
    >
      <p>{{ language.path }}</p>
      <p>{{ language.name }}</p>
      <p>{{ language.completed }}</p>
    </li>
  </ul>
</template>

<script>
export default {
  props: ["languages"],
  methods: {
    handleCompleted(language) {
      language.completed = !language.completed;
    },
  },
};
</script>
