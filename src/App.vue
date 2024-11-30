<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <SfcCounter></SfcCounter>
  <!-- <Form v-slot="$form" :resolver="resolver" :initialValues="initialValues" @submit="onFormSubmit" class="flex flex-col gap-4">
    <div class="flex flex-col gap-1">
      <DatePicker name="date" fluid />
      <Message v-if="$form.date?.invalid" severity="error" size="small" variant="simple">{{ $form.date.error?.message }}</Message>
    </div>
    <Button type="submit" severity="secondary" label="Submit" />
  </Form> -->
</template>

<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import SfcCounter from "./components/SfcCounter.vue";
// import Button from "primevue/button";
// import DatePicker from "primevue/datepicker";
</script>
