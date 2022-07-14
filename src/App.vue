<template>
  <h1>Heelo</h1>
</template>

<script>
export default {
  name: 'App',
  components: {},
  date: () => ({
    list: {
      1: {
        type: 'INCOME',
        value: 100,
        comment: 'Some coment',
        id: 1,
      },
    },
  }),
};
</script>

<style></style>
