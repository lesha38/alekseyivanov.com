<template>
  <div class="developing">
    <p class="developing-desc">
      COMING SOON
    </p>
  </div>
</template>

<script>
  export default {
    name: 'Home',
    data: () => ({

    }),
  };
</script>

<style lang="scss">
  .developing {
    display: flex;
    flex-flow: column nowrap;
    justify-content: center;
    align-items: center;
    background-color: rgba(black, 0.6);
    border-radius: 2px;
    box-sizing: border-box;
    padding: 24px;
  }

  .developing-desc {
    color: white;
    font-weight: 500;
    font-size: 32px;
  }
</style>
