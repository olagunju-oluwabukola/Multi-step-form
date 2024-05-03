<script>
import Step1 from './components/Step1.vue';
import Step2 from './components/Step2.vue';
import Step3 from './components/Step3.vue';
import Step4 from './components/Step4.vue';

export default{
  components :{
    Step1,
    Step2,
    Step3,
    Step4
  },

  data(){
    return{
      isActive : 'step-1'
    }
  }
}

</script>

<template class="body">

<keep-alive>
  <component :is="isActive"/>

</keep-alive>

<div class="btn">
  <button @click="isActive = 'step-1'" class="active">1</button><span>----------</span>
  <button @click="isActive = 'step-2'">2</button><span>-----------</span>
  <button @click="isActive = 'step-3'">3</button><span>-----------</span>
  <button @click="isActive = 'step-4'">4</button>

</div>


  
  

</template>

<style>

button{
background-color: transparent;
border: 1px solid blue;
color: blue;
font-size: 15px;
border-radius: 50px 50px 50px 50px;
width: 3em;
height: 3em;
display: inline;

}

.btn{
  display: flex;
justify-content: center;
background: #fff;
border-radius: 10px 10px 10px 10px;
height: 5em;

}

button:focus{
background-color: blue;
color: #fff;
}

button:visited{
  background-color: blue;
color: #fff;
}
span{
  color: blue;
}

</style>
