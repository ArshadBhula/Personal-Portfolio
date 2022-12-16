<template>
  <h1 class="contactme">Contact Me</h1>
  <form>
    <label>Email :</label>
    <input type="email" required>

    <label>Password :</label>
    <input type="password" required>

    <label>Write your Message :</label>
    <input type="text" required>

    <label>Submit:</label>
    <input type="submit" required>

  </form>


</template>

<script>
export default {

}
</script>

<style scoped>
 body{
 margin: 0;
 background: #eee;
  }
  form{
    max-width: 420px;
    margin: 30px auto;
    background: aliceblue;
    text-align: left;
    padding: 40px;
    border-radius: 10px;
}

label{
    color: #aaa;
    display:inline-block;
    margin: 25px 0 15px;
    font-size: 0.6em;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: bold;
}

input,select{
    display: block;
    padding: 10px 6px;
    width: 100%;
    box-sizing: border-box;
    border: none;
    border-bottom: 1px solid #ddd;
    color: #555;
}

input[type="checkbox"]{
    display: inline-block;
    width: 16px;
    margin: 16px;
    position: relative;
    top: 2px;
}

.pill{
    display: inline-block;
    margin: 20px 10px 0 0;
    padding: 6px 12px;
    background: #eee;
    border-radius: 20px;
    font-size: 12px;
    letter-spacing: 1px;
    font-weight: bold;
    color: #777;
    cursor: pointer;
}
button{
    background: #0b6dff;
    border: 0;
    padding: 10px 20px;
    margin-top: 20px;
    color: white;
    border-radius: 20px;
}
.submit{
    text-align: center;
}
.error{
    color:#ff0062;
    margin-top: 10px;
    font-size: 0.8em;
    font-weight: bold;
}
.contactme{
  text-align: center;
}
</style>