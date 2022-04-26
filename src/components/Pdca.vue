<template>
  <div class="pdca">
    <p>PD</p>
    <p>CA</p>
  </div>
</template>
<style>
.pdca {
  font-size: 200px;
  animation: 0.01s linear 0s infinite revolution;
}
@-webkit-keyframes revolution {
  from {
    transform: rotate(0turn);
  }
  to {
    transform: rotate(1turn);
  }
}
</style>
