<template>
  <header>
    <nav>
      <div>
        <div class="login-comp">
          <div class="form-group">
            <label for="exampleInputEmail1">Email</label>
            <input type="email" class="form-control" id="exampleInputEmail1" />
          </div>
        </div>
        <div class="login-comp">
          <div class="form-group">
            <label for="exampleInputPassword1">Password</label>
            <input type="password" class="form-control" id="exampleInputPassword1" />
          </div>
        </div>
        <div class="login-comp">
          <button class="button-custom">Login</button>
        </div>
      </div>
      <div class="form-check">
        <div class="login-comp">
          <input class="form-check-input" type="checkbox" id="gridCheck" />
          <label class="form-check-label" for="gridCheck">Remember Me</label>
        </div>
        <div class="login-comp">
          <a href>Lost Password?</a>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {};
</script>

<style>
header {
  background-color: #1dafa1;
  position: absolute;
  top: 0px;
  width: 100%;
  height: 20%;
}
nav {
  float: right;
}
.login-comp {
  display: inline-block;
  padding-right: 10px;
  padding-left: 20px;
  width: 33%;
}
.button-custom {
  background-color: #999999;
  border: none;
  color: white;
  padding: 8px 15px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  border-radius: 8px;
}
</style>
