<template>
  <div class="card">
    <div class="card-body">
      <h5 class="card-title">{{ itemTitle }}</h5>
      <p class="card-text">{{ itemContent }}</p>
    </div>
  </div>
</template>

<script>
export default {
  props: { itemTitle: String, itemContent: String, itemPrice: Number },

  // beforeCreate() {
  //   console.log("before create");
  // },
  created() {
    console.log("created");
  }
  // beforeMount() {
  //   console.log("before mount");
  // },
  // mounted() {
  //   console.log("mounted");
  // },
  // beforeDestroy() {
  //   console.log("before destroy");
  // },
  // destroyed() {
  //   console.log("destroyed");
  // }

  
};
</script>