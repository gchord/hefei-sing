<template>
    <div>
      <div class="register-wrap">
        <input type="text" placeholder="请输入用户名">
        <input type="password" placeholder="请输入密码">
        <button>注册</button>
      </div>
    </div>
</template>

<script>
    export default {
        name: "register"
    }
</script>

<style scoped>
  .login-wrap{text-align:center;}
  input{display:block; width:250px; height:40px; line-height:40px; margin:0 auto; margin-bottom: 10px; outline:none; border:1px solid #888; padding:10px; box-sizing:border-box;}
  p{color:red;}
  button{display:block; width:250px; height:40px; line-height: 40px; margin:0 auto; border:none; background-color:#41b883; color:#fff; font-size:16px; margin-bottom:5px;}
  span{cursor:pointer;}
  span:hover{color:#41b883;}
</style>
