<template>
    <div class="overall">
        <div class="title">
            <h1>Work Experience</h1>
        </div>

        <div class="form">
            <label for="">In not more than 200 words, explain your work experience at your former office
              <br>  <input type="text" placeholder="200 words maximum" v-model="previous">
            </label>

          <br>  <label for="">
            How satisfied are you with the work environment? 
            <br>
            <input type="text" placeholder="200 words maximum" v-model="WE">
        </label>

          <br>
        <label for="">
    What can you regard as an acheivement while working there?
    <br>
     <input type="text" placeholder="100 words maximum" v-model="acheivement"></label>
        
        </div>

        
    </div>
</template>

<script>
export  default{
    data(){
        return{
            previous: '',
            WE: '',
            acheivement: ''
        }
    }
}
</script>

<style scoped>
.form{
line-height: 2em;
margin-left: 1em;
font-size: 16px;
}

input{
    border: none;
    border-bottom: 1px solid blue;
    width: 20em;
    outline: none;
    background: transparent;
   
  
}


</style>