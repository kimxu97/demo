<script setup>
import A from './components/A.vue'
import B from './components/B.vue'
import C from './components/C.vue'
</script>

<template>
 <div class="box">
   <A class="a"/>
   <B class="b" />
   <C class="c" />
 </div>
</template>

<style>
.box{
  display: flex;
  align-items: center;
  width: 100vw;
}
.a{
  width: 30%;
}
.b{
  width: 50%;
}
.c{
  width: 20%;
}
</style>
