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
      2: {
        type: 'OUTCOME',
        value: -50,
        comment: 'Some coment',
        id: 2,
      },
    },
  }),
};
</script>

<style></style>
