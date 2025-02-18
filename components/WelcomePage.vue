<script setup>
import LoginForm from "../components/LoginForm.vue"

const loading= ref(false)
</script>

<template>

 <div class="container-fluid mt-4">
    <div class="d-flex flex-column flex-md-row min-vh-100">
      <!-- <div class="p-3   w-100 w-lg-50 d-flex align-items-center justify-content-center"> -->
      <div class="p-3   w-100 w-lg-50 d-flex align-items-center justify-content-center">
     
       <LoginForm></LoginForm>
      </div>
      <div class="p-3  w-100  w-lg-50 mx-5 mx-xl-0  d-flex align-items-center justify-content-center">
       <DetailsComp></DetailsComp>
      </div>
    </div>
  </div>
</template>