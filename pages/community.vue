<template>
  <main>
    <div class="flex justify-between align-center p-5">
      <Header />
      <Nav />
      
    </div>
    <Community />
  </main>

</template>
<script>
export default {
  data() {
    return {
      pageInfo: {
        menuName: "community",
        header: "Community",
      },
    };
  },
};
</script>
