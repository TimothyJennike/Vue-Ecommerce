<template>
        <h2>If you would like more info, feel free to contact us :)</h2>
        <div class="form">
        <form>
         <input type="text" placeholder="Fullname..." v-model="fullname">
         <input type="email" placeholder="Email..." v-model="email">
         <input type="number" placeholder="Age..." v-model="age">
         <input type="submit" id="submit" placeholder="Submit" v-on:click.prevent="submit">
        </form>
      </div>
          
</template>
<script>
export default {
  methods : {
      submit(){
                alert(`${this.fullname} with the email ${this.email} woulld like more info`)
            }
  } 
    
}
</script>
<style>
h2 {
    text-align: center;
}
.form {
    text-align: center;
    width: 250px;
    margin: auto;
}


</style>