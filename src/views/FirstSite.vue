<template>
  <div class="foodwide">
  <h1>Project Name : Food-Worldwide</h1>
  <div class="intro">
  <h3>Description : This was a University Project , where we had to create any Website using HTML. I decided to create a website called Food World-Wide. This online resturant would sell famous dishes of most Countries. </h3>
  <h2>
       
  <div class="imgg">
  <img alt="logo" src="../assets/html.png">
  </div>
  </h2>
  
  <h3 class="note">Note : Please bare in mind that this was my very first site and it has many errors.</h3>

 <button class="myBtn"><a href="https://food-worldwide.netlify.app/">View Site</a></button>

  </div>
  </div>
 
</template>

<script>
export default {

}
</script>

<style>
  .foodwide{
    width: 500px;
    text-align: center;
    margin: 100px auto;
  }
  .intro{
    border-style: double;
    border-color: cadetblue;
    border-width: 4px;
    padding: 30px;
  }

  .myBtn{
    font-size: 30px;
    font-weight: 400;
    padding: 12px;
    border-radius: 7px;
    border-color: rgb(33, 130, 214);
  }

  .myBtn:hover{
    background: #ddd;
  }

  .note{
    /* font-weight: 100; */
    opacity: .6;
  }
</style>