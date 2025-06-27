<script setup lang="ts">
const inputValue = ref('')
</script>

<template>
  <div class="px-10">
    <InputText type="text" v-model="inputValue" />
    
    <Panel header="Input Value:" class="mt-4">
    <p class="m-0">
{{ inputValue }}
    </p>
</Panel>

  </div>


</template>
