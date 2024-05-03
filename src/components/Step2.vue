<template>
<div class="overall">
    <div class="title">
        <h1>soft skills</h1>
    </div>

    <div class="check">
        <h3>choose based on your level of proficiency</h3>
        <label for=""><input type="checkbox">Team work</label> <br>
        <label for=""><input type="checkbox">Organization</label> <br>
        <label for=""><input type="checkbox">Monitoring</label> <br>
        <label for=""><input type="checkbox">Evaluation</label>
    </div>
    <div class="check">
        <h3>on a scale of 1 to 10, how fast can you adapt to a new environment?</h3>
    <label for=""><input type="radio">0-2</label>
    <label for=""><input type="radio">3-5</label>
    <label for=""><input type="radio">5-8</label>
    <label for=""><input type="radio">8-10</label>
    </div>

    <div class="check">
        <h3>How often do you experience mood swing?</h3>
        <select name="" id="">
            <option value="">Never</option>
            <option value="">Rearly</option>
            <option value="">Often</option>
            <option value="">Always</option>
        </select>
    </div>
</div>


</template>

<style>
.title{
    padding-top: 2em;
  text-align: center;
  color: rgb(3, 3, 114);
  text-transform: uppercase;
}

.overall{
background: #fff ;
border-radius: 10px 10px 10px 10px;
height: 30em;
margin-top: 5em;
}

.check{
margin-left: 3em;

}
label{
    font-size: 15px;
    margin: 10px;
}
option{
    background: blue;
    color: #fff;
 
}




</style>