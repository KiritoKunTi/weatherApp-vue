<script>
</script>

<template>
  <div class="wrapper">
    <h1>Weather App</h1>
    <p>To know weather on your city</p>
    <input type="text" placeholder="Print a city">
    <button>Get Weather</button>
  </div>
</template>

<style scoped>
.wrapper {
  width: 900px;
  height: 500px;
  border-radius: 50px;
  background-color: #1f0f24;
  padding: 20px;
  text-align: center;
  color: #fff;
}
.wrapper h1 {
  margin-top: 50px;
}
.wrapper input {
  margin-top: 30px;
  background: inherit;
  border: 0;
  border-bottom: 2px solid #110813;
  color: #fcfcfc;
  padding: 5px 8px;
  font-size: 14px;
  outline: none;
}
.wrapper input:focus {
  border-bottom-color: #6e2d7d;
}
.wrapper button {
  background-color: #e3bc4b;
  color: #fff;
  border-radius: 10px;
  border: 2px solid #b99935;
  padding: 10px 15px;
  margin-left: 20px;
  cursor: pointer;
  transition: transform 500ms ease;
}
.wrapper button:hover {
  transform: scale(1.1) translateY(-5px);
}
</style>
