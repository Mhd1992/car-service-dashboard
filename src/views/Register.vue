<template>
    <div class="Register">
      <h1>This is an Register page</h1>
      <div class="container">
        <div class="card">
          <div class="card-header">  <h3>Sign In</h3></div>
          <div class="card-content">
            <form>
          

            <div class="form-group">
                <label>Email address</label>
                <input type="email" class="form-control form-control-lg" />
            </div>

            <div class="form-group">
                <label>Password</label>
                <input type="password" class="form-control form-control-lg" />
            </div>

            <div class="form-group">
                <label>Phone</label>
                <input type="phone" class="form-control form-control-lg" />
            </div>
        </form>
          </div>
          <div class="card-footer">
            <button type="submit" class="btn btn-dark btn-lg btn-block">Sign In</button>

<p class="forgot-password text-right mt-2 mb-4">
    <router-link to="/forgot-password">Forgot password ?</router-link>
</p>
          </div>
        </div>

    </div>
 
    </div>
  </template>
  <style scoped>
  
.inner-block {
  width: 450px;
  margin: auto;
  background: #ffffff;
  box-shadow: 0px 14px 80px rgba(34, 35, 58, 0.2);
  padding: 40px 55px 45px 55px;
  border-radius: 15px;
  transition: all .3s;
}
  </style>