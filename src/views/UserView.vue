<template>
    <div class="user">
      <h1>This is an Users page</h1>
      <div class="container">
        <div class="form-group">
  <label for="usr">Name:</label>
  <input type="text" class="form-control" id="usr">
</div>
<div class="form-group">
  <label for="pwd">Password:</label>
  <input type="password" class="form-control" id="pwd">
</div>
      </div>
    </div>
  </template>
 
 <script lang="ts" setup>
import axios from 'axios'
//https://172.20.10.2:6001/api/Categorys/GetAll
var users =  axios.get('https://localhost:6001/api/Categorys/GetAll');

</script>