<template>
  <div id="app">
    <h1>Hello World!</h1>
    <div>
      <router-link to="/">Go to root!</router-link>
      <router-link to="/firstPage">Go to FirstPage</router-link>
      <router-link to="/secondPage">Go to SecondPage</router-link>
    </div>
    <router-view></router-view>
  </div>
</template>