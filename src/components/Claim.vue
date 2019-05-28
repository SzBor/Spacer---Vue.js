<template>
  <div class="claimWrapper">
    <h1 class="claim">SPACER</h1>
    <p class="subclaim">
      Begin an amazing journey throughout the galaxy
      and discover places you have never seen.
    </p>
    <p class="subclaim">Type in anything space related to launch!</p>
  </div>
</template>

<script>
export default {
  name: "Claim"
};
</script>
<style lang="scss" scoped>
.claimWrapper {
  display: flex;
  text-align: center;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.claim {
  font-size: 50px;
  margin: 0;
}

.subclaim {
  margin: 20px 0 0 0;
  font-size: 13px;
}
</style>

