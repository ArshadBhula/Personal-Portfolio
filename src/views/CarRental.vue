<template>
<div class="fooodwide">
 <h1>Project Name : Car Rental Application</h1>
  <div class="introo">
 <h3>Description: This was a University project where I had to create a Car Rental Application for Bowman Car Hire. This Application should be able to keep record of cars that are available to hire , cars that not available , be able to serach cars , add cars and much more.</h3>

     <br>

    <div>
  <img alt="logo" src="../assets/sql.png">
  <img alt="logo" src="../assets/c.png">
 
  </div>
  <br>

 <h3 class="note">Note : This Project will not have a site due to it being a C# and SQl Project and not a web development Project. Images will be provided below . </h3>
 <br>
     <div class="imgggg">
    <button @click="toggleImg" class="toggleBtn">
        <span v-if="showImg">Hide Images</span>
        <span v-else>Show Images</span>
        <br>
    </button>
    <br>
    <div v-if="showImg">
        <br>
        <br>
            <div>
    <img alt="logo" src="../assets/ss1.png">
    <img alt="logo" src="../assets/ss2.png">
    
  </div>
    </div>
    </div>

 </div>
 </div>

</template>

<script>
  export default{
    data(){
        return{
            showImg : false
        }
    },
    methods : {
        toggleImg(){
            this.showImg = !this.showImg
        }
    }
  }
</script>

<style>

.toggleBtn{
    padding: 10px;
    border-radius: 7px;
    border-color: rgb(33, 130, 214);
    font-weight: 400;
    font-size: 15px;
     cursor: pointer;

}
.toggleBtn:hover{
   background: rgb(187, 177, 177);
}

.fooodwide{
    width: 800px;
    text-align: center;
    margin: 100px auto;
  }
  .introo{
    border-style: double;
    border-color: cadetblue;
    border-width: 4px;
    padding: 25px;
  }
     .note{
    /* font-weight: 100; */
    opacity: .6;
  }

</style>