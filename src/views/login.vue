<template>
    <div>
      <h1>login is rendering</h1>
  
      <!-- <div class="center" :style="`background-color:${randomColor()}`"> -->
      <div class="center">
        <h1>Login</h1>
  
        <v-row>
          <v-col cols="10" offset="1" sm="6" offset-sm="3" md="4" offset-md="4">
          
            <v-avatar color="primary" size="85"
              ><v-img src="@/assets/logo.png"></v-img
            ></v-avatar>
  
            <v-text-field label="Regular" placeholder="Username"></v-text-field>
  
  
            <v-btn block> Block Button </v-btn>
          </v-col>
        </v-row>
        <!-- for a set of rows, the colums that will be rendered out of the 12 are 10, offset means the number of cols it leaves, so we get everything in the center 10 cols -->
      </div>
    </div>
  </template>
  
  <script >
  export default {};
  </script>
  
  <style lang="scss" scoped></style>