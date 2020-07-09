<template>
  <div>
    <input type="text" name="regnr" placeholder="Registeringsnummer" v-model="regnr" />
    <input type="text" name="pris" placeholder="Inköpspris" />
    <button type="submit" @click="search">Sök</button>
  </div>
</template>

<script>
export default {
  name: "SearchInput",
  data: () => {
    return {
      regnr: "h"
    };
  },
  methods: {
    search: function() {
      console.log(this.regnr);
    }
  }
};
</script>

<style>
</style>