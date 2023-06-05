<script setup>

</script>

<template>
<nav>
    
</nav>
<p></p>
<h1 class="center">Harmonize.</h1>
<p></p>
<h2 class="center">Create an account</h2>
<v-sheet width="300" class="mx-auto">
    <v-form @submit.prevent>
      <v-text-field
        v-model="firstName"
        :rules="rules"
        label="First name"
      ></v-text-field>
      <v-btn type="submit" block class="mt-2">Submit</v-btn>
    </v-form>
  </v-sheet>
<router-view></router-view>
</template>


<style>
body {
background-color: #020f4c;
}
.center {
    text-align: center;
}
h1, h2 {
    color:greenyellow;
}
form {
    color:#020f4c;
    background-color: transparent;
}
</style>