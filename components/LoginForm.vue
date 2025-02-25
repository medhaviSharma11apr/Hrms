<template>

  <div class="form mycustom-form">
    <div>
      <b-form>
        <LogoCustom image="./images/logo.png" height="60" width="300"></LogoCustom>
        <div class="welcome my-4">
          <p>Welcome to</p>
        </div>
        <div class="hrms">
          <h4>Human Resource Management System</h4>
        </div>
        <div class="username">

          <b-form-group class="my-3">
            <b-form-input id="input-1" type="email" placeholder="Username" required ></b-form-input>
          </b-form-group>
        </div>

        <div class="password">
          <b-form-group>
            <b-form-input id="input-1" type="email" placeholder="Password" required ></b-form-input>
          </b-form-group>
        </div>

        <div class="d-flex align-items-end justify-content-end pt-2 pb-2">
          <span>
            Forgot Password
          </span>
        </div>

        <div
          class="container mt-2 bg-secondary d-flex align-items-center justify-content-center py-2  rounded text-white"
          ,style="background-color: #495057;">
          Login
        </div>

        <div class="container mt-2 bg-primary d-flex align-items-start  py-2  rounded text-white"
          ,style="background-color: #495057;">
          <div class="h-2 bg-white border border-primary">
            <img src="public/images/google.jpeg" height="20" width="20">
          </div>

          <div>
            <p class="p-0">
              Login wiyh your company google account
            </p>
          </div>
        </div>
      </b-form>

    </div>
  </div>
</template>

<style scoped>
.form input::placeholder{
 font-size: .95rem;
 font-weight: 100;
letter-spacing: 0.5px;
    color: #495057;
}
.username input:focus{
   border-bottom: 3px solid #50b798;;
   box-shadow: none !important; 
   font-family: Montserrat, sans-serif;
}
.password input{
   background-color: #f2f2f2;
   border: none;
}

.password input:focus{
   border-bottom: 3px solid #50b798;
   border-top: 0px;
   border-left: 0px;
   border-right: 0px;
   box-shadow: none !important; /* Remove any shadow */
   font-family: Montserrat, sans-serif;
}


.welcome {
  margin: 0;
  font-family: sans-serif;
  font-size: 1rem;
  font-weight: 100;
  line-height: 1.5;
  color: #495057;
  text-align: left;

}


span {
  color: #218bc3;
  font-size: .8em;
}
</style>


<script setup>
</script>