<template>
  <div class="home">
    <h1>Home</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam
      voluptates, quod, quia, voluptate quae voluptatem quibusdam consequuntur
      quos voluptatum quas quidem. Quisquam, quae. Quisquam voluptates, quod,
      quia, voluptate quae voluptatem quibusdam consequuntur quos voluptatum
      quas quidem. Quisquam, quae.
    </p>
    <p>{{ message }}</p>
    <ul>
      <li v-for="name in names" :key="name">
        {{ name }}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "Hello from HomeView",
      names: ["John", "Jane", "Joe", "Janet", "Job", "Johndiddles", "Jonathan"],
    };
  },
};
</script>
