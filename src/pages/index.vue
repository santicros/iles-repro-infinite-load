<template>
  <div>
    <h1>Hello world</h1>
    <!-- adding any client:idle or client:load or client:... makes Firefox infinite load, but the button is interactive -->
    <SimpleCounter client:idle></SimpleCounter>
  </div>
</template>
