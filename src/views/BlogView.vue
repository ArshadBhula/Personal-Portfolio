<template>
  <div class="blog">
  <h1>Blog News : </h1>
  </div>
  <br>
   <div class="blog2">
    <h4>02/12/2022</h4>
    <div class="blog22">
    <h2>Topic : Vue.js</h2>
    <h3>What is Vue.js?</h3>
    <h5>Vue.js is a JavaScript FrameWork. It is used to create fast and reliable web applications and single page applications. The benefit of using vue.js is that it only sends one request to the server when you enter the website and the server only returns the blank bare-bones HTML document and the Vue JavaScript Bundle and contains no visible content. The JavaScript Bundle then takes full control of the website in the browser. This makes the Website feel much more faster and smoother.</h5>
    <h3>How long will it take to learn Vue.js?</h3>
    <h5>It could take an average person atleast 1 - 2 weeks depending on your programmer skills . An experienced programmer could learn the basic concepts within a per hours. It all depends on how much time you spend on learning it. If you plan on learning a JavaScript Framework I suggest you start with Vue.js as it is simple and easy to understand. </h5>
    <h3 class="note">Note : It's recommended that people are fluent in Javascript before attempting to learn Vue.</h3>
    <h4>Link for Vue.js Tutorial for Beginners below : </h4>
    <button class="myBtn"> <a href="http://www.youtube.com/watch?v=YrxBCBibVo0&list=PL4cUxeGkcC9hYYGbV60Vq3IXYNfDk8At1">Full Course</a></button>
  </div>
  </div>

  <div class="blog2">
    <h4>11/12/2022</h4>
    <div class="blog22">
     <h2> Topic : Hosting your Site for Free </h2>
     <h4>Alot of times Web developers want to deploy their work so that everyone can view it. However most of the times this cost money due to domain names , hosting and much more . The method im about to show you today will allow you to host your website completly free . </h4>
     <br>
     <h3 class="note">Note : You will need a GitHub Account for this to work.</h3>
     <ul class="listt">
     <li><h5>Step 1 : Go to <a href="http://www.netlify.com">https://netlify.com</a></h5></li>
     <li><h5>Step 2 : Create an Account/Login</h5></li>
     <li><h5>Step 4 : Once you are logged in , link your GitHub to your Netlify Account. </h5></li>
     <li><h5>Step 5 : Make Sure the website that you want to deploy is in a repository on your GitHub Account . </h5></li>
     <li><h5>Step 6 : Once Netlify Authorizes your GitHub Account , it will give you access to all your repositories</h5></li>
     <li><h5>Step 7 : Select the repository/website you want to deploy.</h5></li>
     </ul>

     <h4>Having Trouble with Netlify? </h4>
     <div class="linkk">
      <a href="https://www.youtube.com/watch?v=cUMUTS2ybhg&t=112s">Tutorial</a>
    </div>
    </div>
  </div>

</template>

<script>
export default {
data(){
  return{
    youtube : 'https://www.youtube.com/watch?v=YrxBCBibVo0&list=PL4cUxeGkcC9hYYGbV60Vq3IXYNfDk8At1'
  }
}
}
</script>

<style scoped>
  .blog{
    border-style: double;
    border-color: rgb(168, 183, 197);
    border-radius: 10px;
    width: 800px auto;
    text-align: center;
  }

  .blog2{
    text-align: left;
  margin: 100px auto;
   border-style: double;
   border-color: #42b983;
   max-width: 700px;
  border-width: 5px;
  padding: 30px;
  border-radius: 10px;
  background-color: aliceblue;
  font-size: 20px;
  align-content: center;
  }
  .blog22{
    align-content: center;
    text-align: center;
  }

  .listt{
    text-align: left;
  }
  .linkk{
    font-weight: bold;
  }
</style>