<script setup>
import LoginForm from "./LoginForm.vue"

const loading= ref(false)
</script>

<template>

 <div class="container-fluid mt-4">
    <div class="d-flex flex-column flex-md-row min-vh-100">
      <div class="p-3 bg-success text-white flex-fill d-flex align-items-center justify-content-center">
     
       <LoginForm></LoginForm>
      </div>
      <div class="p-3 bg-danger text-white flex-fill d-flex align-items-center justify-content-center">
         <LoginForm></LoginForm>
      </div>
    </div>
  </div>
</template>