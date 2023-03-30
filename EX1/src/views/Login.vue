


<template>
  <div class="wrappers">
    <div style="width:100%; display:flex;flex-direction:column;">
      <img src="https://www.w3schools.com/howto/img_avatar2.png" alt="profile" />
      <div class="input">
        <label for="username">Username</label><br />
        <input type="text" name="" id="email" ref="email" placeholder=" Enter email" required>
      </div>
      <div class="input">
        <label for="password">Password</label><br />
        <input type="password" name="" id="password" ref="password" placeholder=" Enter password" required>
      </div>
      <div class="forget-password">
        <a href="">Forget Password?</a>
      </div>
      <div class="input">
        <button id="login" onclick="login();">Login</button>
      </div>
    </div>
  </div>
</template>

<style>
.wrappers {
  display: flex;
  width: 500px;
  border: 1px solid rgb(13, 12, 12);
  padding: 20px;
  text-align: center;

}

.wrappers img {
  width: 200px;
  border-radius: 100%;
}

.forget-password {
  display: flex;
  justify-content: right;
  text-decoration: underline;

}

.input {
  width: 100%;
  text-align: left;
}

.input input {
  width: 100%;
  height: 50px;
  padding-left: 10px;
  margin: 10px 10px 10px 0px;
}

.input button {
  width: 100%;
  height: 50px;
  margin-top: 10px;
  border: 0px solid black;
  color: white;
  background-color: rgb(4, 170, 109);
}

.content p {
  margin-top: 10px;
}

.content button {
  margin-left: 10px;
  width: 90px;
  height: 25px;
  color: white;
  background-color: gray;
  border: 0px;
  border-radius: 2px;
  margin-top: 5px;
}

@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}</style>