<template>
  <div class="pdca">
    <p>PD</p>
    <p>CA</p>
  </div>
</template>
<style>
.pdca {
  font-size: 200px;
  animation: 1s linear 0s infinite revolution;
}
.pdca p {
  animation: 1s linear 0s infinite text;
}
@-webkit-keyframes revolution {
  from {
    transform: rotateX(0deg) rotateY(0deg) rotateZ(0deg);
    color: hwb(0 0% 0%);
  }
  to {
    transform: rotateX(360deg) rotateY(360deg) rotateZ(360deg);
    color: hwb(356 0% 0%);
  }
}
</style>
