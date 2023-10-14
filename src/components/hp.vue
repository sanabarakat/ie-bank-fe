<template>
  <div>
    <h1>IE Bank</h1>
    <p>The Best Bank</p>
    <img src="../components/bank.jpg" alt="IE Tower">
    <br>
    <router-link to="/accounts" class="button">View Accounts</router-link>
    <router-link to="/skull" class="button">Skull</router-link>
  </div>
</template>




<style scoped>
div {
  background-color: rgba(14, 217, 11, 0.208);
  padding: 20px;  
  text-align: center;
}
h1 {
  color: rgb(14, 138, 7);
}
p {
  font-size: 1.2rem;
}

img {
max-width: 100%; 
}
.button {
  display: inline-block;
  padding: 10px 20px;
  background-color: #2dac0ae1;
  color: #fff;
  text-decoration: none;
  border: none;
  border-radius: 5px;
  font-size: 1.2rem;
  margin-top: 1rem;
  cursor: pointer;
  margin-right: 10px;
}

.button:hover {
  background-color: #286e0b;
}
</style>