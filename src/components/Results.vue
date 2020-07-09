<template>
  <div>
    <p>Den drar {{literPerMil}} l/mil</p>
    <p>Skatten ligger på {{skatt}} kr</p>
  </div>
</template>

<script>
export default {
  name: "Results",
  data: () => {
    return {
      literPerMil: 0.68,
      skatt: 2600
    };
  }
};
</script>

<style>
</style>