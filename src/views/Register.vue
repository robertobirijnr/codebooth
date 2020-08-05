<template>
  <div>
    <div class="signin">
      <form>
        <h2>Register</h2>
        <input type="text" name="username" placeholder="Enter your fullname here" />
        <input type="email" name="email" placeholder="Enter your email here" />
        <input type="password" name="password" placeholder="Enter your password" />
        <br />
        <br />
        <button>Register</button>

        <br />
        <br />Already have account ?
        <router-link to="/login">Signin</router-link>
      </form>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style  scoped>
.reset,
.forgotpassword {
  margin-right: 0px;
  font-family: Tahoma, Geneva, sans-serif;
  font-size: 13px;
}

h2 {
  color: #ee82ee;
  font-weight: bold;
  margin-bottom: 15px;
}
button {
  background: violet;
  color: white;
  width: 150px;
  height: 50px;
  cursor: pointer;
  text-decoration: none;
  font-size: 16px;
  border: none;
}
router-link,
a {
  text-decoration: blink;
  color: #ee82ee;
}

#container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  width: 100%;
}

.signin {
  background: #fff;
  padding: 40px;
  border-radius: 7px;
  box-shadow: bisque;
  width: 350px;
  margin: auto;
  margin-top: 80px;
  height: 400px;
  margin-left: 600px;
}

form {
  width: 240px;
  text-align: center;
}

input {
  width: 240px;
  text-align: center;
  background: transparent;
  border: none;
  border-bottom: 1px solid #ee82ee;
  font-family: "Play", sans-serif;
  font-size: 16px;
  font-weight: 200px;
  padding: 10px 0;
  transition: border 0.5s;
  outline: none;
  color: #ee82ee;
}
</style>