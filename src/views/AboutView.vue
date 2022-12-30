<template>
  <div class="home">
    <h1>About</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam
      voluptates, quod, quia, voluptate quae voluptatem quibusdam consequuntur
      quos voluptatum quas quidem. Quisquam, quae. Quisquam voluptates, quod,
      quia, voluptate quae voluptatem quibusdam consequuntur quos voluptatum
      quas quidem. Quisquam, quae.
    </p>
    <LanguageList :languages="languages" />
  </div>
</template>

<script>
import LanguageList from "../components/LanguageList.vue";

export default {
  data() {
    return {
      languages: [
        { name: "Html", completed: true, path: "frontend" },
        { name: "Css", completed: true, path: "frontend" },
        { name: "JavaScript", completed: true, path: "frontend" },
        { name: "React", completed: true, path: "frontend" },
        { name: "Vue", completed: false, path: "frontend" },
        { name: "Node", completed: false, path: "backend" },
        { name: "Express", completed: false, path: "backend" },
        { name: "MongoDB", completed: false, path: "backend" },
        { name: "SQL", completed: false, path: "backend" },
        { name: "Java", completed: false, path: "backend" },
        { name: "C#", completed: false, path: "backend" },
        { name: "C++", completed: false, path: "backend" },
        { name: "C", completed: false, path: "backend" },
        { name: "Ruby", completed: false, path: "backend" },
        { name: "Ruby on Rails", completed: false, path: "backend" },
        { name: "PHP", completed: false, path: "backend" },
        { name: "Laravel", completed: false, path: "backend" },
        { name: "Swift", completed: false, path: "mobile" },
        { name: "Kotlin", completed: false, path: "mobile4" },
      ],
    };
  },
  components: { LanguageList },
};
</script>
