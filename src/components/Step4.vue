<template>
    <div class="overall">
        <div class="title">
            <h1>Convince us to give you the role</h1>
        </div>
        <div class="form">
            <label for="">
                why should you be considered for this role? <br>
                <input type="text" placeholder="200 words maximum" v-model="consideration">
            </label> <br>

            <label>
                What impact are you cabable of effecting on the organization?
                <br>
                <input type="text" placeholder="100 words maximum" v-model="cabable">

            </label> 
            <br>

            <label for="">What are your reasons for choosing us?  <br>
                <input type="text" placeholder="Keep it short and precise" v-model="reasons">
            </label>

            


        </div>
        <button class="button" @click="clicked()">Submit</button>

    </div>

    

</template>

<script>
export default{
    data(){
        return{
           consideration: '',
           capability: '',
           reasons:'', 
        }
    },
    methods:{
        clicked(){
            return alert('submitted successfully')
        }
    }
}
</script>
<style  scoped>
input{
    border: none;
    border-bottom: 1px solid blue;
    width: 20em;
    outline: none;
    background: transparent;
}

.form{
line-height: 1.8em;
margin-left: 3em;
font-size: 16px;
}

.button{
    background: blue;
    border-radius: 10px 0 10px 0;
    width: 5em;
    color: #fff;
    margin: 1em 0 0 1em;
    
}
</style>