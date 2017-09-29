<template>
  <div id="login-page">
    <!-- <div class="columns is-centered">
      <div class="column is-half centered" style="padding: 64px 32px">
        <p class="title">Welcome To Asia Commerce Admin!</p>
      </div>
    </div> -->
    <div class="columns is-centered">
      <div class="column is-one-quarter is-half-mobile is-offset-one-quarter-mobile is-two-thirds-tablet admin-login">
        <div class="field centered">
            <label for="" class="title"> Your Image will Be here</label>
            <label class="label light-label">Admin Panel</label>
        </div>
        <div>
          <div class="field">
            <div class="control">
              <input class="input" v-model="email" type="email" name="email" placeholder="Email">
            </div>
          </div>
          <div class="field">
            <div class="control">
              <input class="input" v-model="password" type="password" placeholder="Password">
            </div>
          </div>
          <div style="padding-top: 45px;" class="columns">
              <button @click="submit" class="column button is-info p-0">Login</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js PWA'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  #login-page {
    position: relative;
    overflow: hidden;
    width: 100%;
    height: 100%;
    background: url('https://cdn.pixabay.com/photo/2017/09/07/17/27/background-2726039_960_720.png'), no-repeat;
    background-size: cover;
  }
  .admin-login {
    position: absolute;
    top: 25%;
    background-color: white;
    padding: 48px;
  }
</style>
