<template>
  <div class="register">
        <h2>ĐĂNG KÍ</h2>
        <form @submit.prevent="register">
          <label for="email">Email</label>
          <br>
          <input type="text" name="email" id="email" v-model="email" value="email" placeholder="nhập email">
          <br>
          <label for="password">Password</label>
          <br>
          <input type="text" name="password" id="password" v-model='password' value="password" placeholder="nhập password">
          <br>
           <button @click.prevent='btn'>Đăng Kí</button>
        </form>
    </div>
</template>

<script>
import axios from 'axios'
export default {
  data(){
    return{
      
    }
  }
  
}
</script>










