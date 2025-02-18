<template>

<div class="form">
   <div>
    <b-form >
       <LogoCustom image="./images/logo.png" height="60" width="300"></LogoCustom>
       <div class="welcome my-4">
         <p>Welcome to</p>
       </div>
         <div class="hrms">
            <h4>Human Resource Management System</h4>
         </div>
         <div class="username">
      
        <b-form-group class="my-3" >
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
    
         <div class="container mt-2 bg-secondary d-flex align-items-center justify-content-center py-2  rounded text-white" ,style="background-color: #495057;" >
            Login 
        </div>
  
          <div class="container mt-2 bg-primary d-flex align-items-start justify-content-center py-2  rounded text-white" ,style="background-color: #495057;" >
           <div class="h-2">
            
           </div>
            Login 
        </div>
         
        
    
      

       
    </b-form >
   
  </div>
</div>
</template>

<style scoped>
.custom-bg-color {
  background-color: #495057; /* Dark gray background */
}

.welcome{
    margin: 0;
    font-family: sans-serif;
    font-size: 1rem;
    font-weight: 100;
    line-height: 1.5;

     color: #495057;
    text-align: left;
    
}
.password {
  background-color: #f0f0f0; /* Light gray background */
  border: 2px solid #ccc; /* Border with color */
    border-radius: 8px;

}
.password .b-form-input {
  border: 1px solid #ccc; /* Border for input field */
  padding: 10px;
  border-radius: 4px;
}
span{
        color: #218bc3;
            font-size: .8em;
}
</style>


<script setup>
</script>