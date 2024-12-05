<template>
<div class="center">
  <div class="q-pa-md row items-start q-gutter-md">
  

    <q-card
      class="my-card text-white"
      style="background: radial-gradient(circle, #35a2ff 0%, #014a88 100%)"
    >
      <q-card-section>
        <div class="text-h6">Grupa 6 kolokvij</div>
        <div class="text-subtitle2">by Tomislav Matejcic</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        {{ lorem }}
      </q-card-section>
    </q-card>
</div>
  </div>
</template>

<script setup>
defineOptions({
  name: 'IndexPage'
});
</script>
