<template>
  <div class="hello">
      
      <div id="login">
        <div class="container">
            <div id="login-row" class="row justify-content-center align-items-center">
                <div id="login-column" class="col-md-12">
                    <div id="login-box" class="col-md-12 mx-auto">
                        <form id="login-form" class="form" action="" method="post" autocomplete="off">
                            <h3 class="text-center" style="color: #42ec98;">LOGIN</h3>
                            <div class="form-group">
                                <label for="username" style="font-weight: bold; color: #42ec98;">USERNAME:</label><br>
                                <div class="border-bottom-1">
                                  <input type="text" name="username" id="username" class="form-control-plaintext" placeholder="Isi username...." style="border:0px solid">
                                </div>
                            </div>
                            <div class="form-group">
                                <label for="password" style="font-weight: bold; color: #42ec98;">PASSWORD:</label><br>
                                <div class="border-bottom border-bottom-1">
                                  <input type="password" name="password" id="password" class="form-control-plaintext" placeholder="Isi password...">
                                </div>
                            </div>
                            <div class="form-group">
                                <input type="submit" name="submit" class="btnSubmit float-right" value="LOGIN">
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    body {
      margin: 0;
      padding: 0;
      height: 100vh;
    }
    #login .container #login-row #login-column #login-box {
      margin-top: 160px;
      max-width: 600px;
      height: 320px;
    }
    #login .container #login-row #login-column #login-box #login-form {
      padding: 20px;
    }
    #login .container #login-row #login-column #login-box #login-form #register-link {
      margin-top: -85px;
    }

    .btnSubmit
    {
        border-radius: 70mm;
        margin-top: 8mm;
        padding: 3mm 10mm;
        border: none;
        cursor: pointer;
        background: #42ec98;
        color: #FFFFFF;
        font-weight: bold;
        box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
    }
    .border-bottom-1 {
        border-bottom: 2px solid #42ec98 !important;
    }
    .form-control-plaintext
    {
      outline: 0;
    }
</style>