<template>
  <div class="box">
  <div class="contact-title">
      <h1>Send a message to request a painting!</h1>
      <h2>It could be anything</h2>
  </div>
  <div class="contact-form">
      <form id="contact-form" method="post" action="">
        <input name="name" type="text" class="form-control" placeholder="Your Name" required><br>
        <input name="email" type="email" class="form-control" placeholder="Your Email" required><br>
        <textarea name="message" class="form-control" placeholder="Message" rows="4" required></textarea><br>
        <input type="submit" class="form-control submit" value="SEND MESSAGE">
      </form>
  </div>
  </div>
</template>
<style>
  .box{
  text-align: center;

  }
  .content-title{
    margin-top: 100px;
    color: #fff;
    text-transform: uppercase;
    transtion: all 4s ease-in-out;
  }
  .content-title h1{
    font-size: 32px;
    line-height: 10px;
  }
  .content-title h2{
    font-size: 16px;
  }
  form{
    margin-top: 50px;
    transition: all 4s ease-in-out;
  }
  .form-control{
    width: 600px;
    background: transparent;
    border: none;
    outline: none;
    border-bottom: 1px solid gray;
    color: #fff;
    font-size: 18px;
    margin-bottom: 16px;
  }
  input{
    height: 45px;
  }
  form .submit{
    background: #ff5722;
  }

</style>
