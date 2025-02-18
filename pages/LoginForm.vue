<template>

<div class="form">
   <div>
    <b-form >
       <LogoCustom image="./images/logo.png" height="60" width="300"></LogoCustom>
       <div class="welcome">
         <p>Welcome to</p>
       </div>
         <div class="hrms">
            <h4>Human Resource Management System</h4>
         </div>
         <div class="username">
    
        <b-form-group >
        <b-form-input
          id="input-1"
        
          type="email"
          placeholder="Username"
          required
        ></b-form-input>
        </b-form-group>
         </div>

        <div class="password">
        <b-form-group >
        <b-form-input
          id="input-1"
          type="email"
          placeholder="Password"
          required
        ></b-form-input>
        </b-form-group>
         </div>
        
         <div class="d-flex align-items-end justify-content-end pt-2 pb-2">
              <span>
            Forgot Password
         </span>
         </div>
         
        
       <b-button block variant="primary" size="lg">Block Level Button</b-button>

    <div class="container mt-2">
    <button class="btn btn-primary d-flex align-items-start">
    <img src="/images/logo.png" alt="Logo" class="logo me-2" width="20" height="20" />
      
        <p >
            Login with your company google account 
        </p>
     
    </button>
   </div>
       
    </b-form >
   
  </div>
</div>
</template>

<script setup>
</script>