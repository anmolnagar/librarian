<template>
    <div>

    <v-app>
    <v-app-bar app color="white" light>
      <div class="d-flex align-center" @click="$router.push('/')">
        <v-img
          alt="Logo"
          class="shrink mr-2"
          contain
          src="@/assets/logo.png"
          transition="scale-transition"
          width="40"
        />
        {{ $const.APP_NAME }}
        <!-- we had directed $const to AppConstants in main. here we access APP_NAME variable using const -->
      </div>

      <v-spacer></v-spacer>

      <v-btn target="_blank" text>
        <span class="mr-2">Login</span>
        <v-icon>mdi-account-circle</v-icon> 
      </v-btn>
      <!-- we took the icon from vuetify: https://v2.vuetifyjs.com/en/components/icons/ -->
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>

    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
</style>