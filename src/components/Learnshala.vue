<template>
  <div class="learnshala">
    <img v-scrollanim alt="Vue logo" height="100" width="100" src="../assets/books.png" />
    <br />
    <br />
    <h2 v-scrollanim>About Learnshala</h2> 
    <p v-scrollanim>New Web App on Sharda University. This is a dummy app just for practice.</p>
  </div>
</template>

<style lang="scss" scoped>
  .before-enter {
    opacity: 0;
    transform: scale(.5) rotateZ(-25deg);
    transition: all 1s ease-out;
  }
  .enter {
    opacity: 1;
    transform: scale(1) rotateZ(0deg);
  }

</style>