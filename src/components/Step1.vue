<template>

    <div class="overall">
        <div class="title">
      <h1>Personal Information</h1>
    </div>
    <div class="form">
        <label for="">Name: <br>
        <input type="text" v-model="name" placeholder="Your answer">
      </label> <br>
      <label for="">Email: <br>
        <input type="Email" v-model="Email" placeholder="your answer">
      </label> <br>
      <label for="">Contact: <br>
        <input type="text" v-model="contact" placeholder="your answer">
      </label> <br>
      <label for="">Next of kin: <br>
        <input type="text" placeholder="your answer"> <br>
        <label for="">Home Address: <br>
        <input type="text" placeholder="your answer">
      </label>
      </label>
    </div>

      
    
    </div>
   



</template>

<script>
export default{
    data(){
        return{
            name: '',
            Email: '',
            contact : '',
            next: ''

        }
    }
}
</script>

<style scoped>



.title{
  padding-top: 2em;
  text-align: center;
  color: rgb(3, 3, 114);
  text-transform: uppercase;
  
}

.form{
line-height: 1.8em;
margin-left: 3em;
font-size: 16px;
}
input{
    border: none;
    border-bottom: 1px solid blue;
    width: 20em;
    outline: none;
    background: transparent;
   
  
}

label{
 padding-top: 10px;
}

.overall{
background: #fff ;
border-radius: 10px 10px 10px 10px;
height: 30em;
margin-top: 5em;


}
</style>