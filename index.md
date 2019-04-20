<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>login in</title>
  <style>
    body{
      margin: 0;
      padding: 0;
      background: #000000;
      font-family: sans-serif;
    }
    .box{
      width: 300px;
      height: 285.867px;
      padding: 39px;
      position: absolute;
      top: 50%;
      left: 50%;
      justify-content: center;
      background: #222222;
      text-align: center;
      transform: translate(-50%,-50%);
    }
    .box:before {
      content:"";
      position:absolute;
      top:-2px;
      right:-2px;
      bottom:-2px;
      left:-2px;
      background: #fff;
      z-index:-1;
    }
    .box:after {
      content:"";
      position:absolute;
      top:-2px;
      right:-2px;
      bottom:-2px;
      left:-2px;
      background: #fff;
      z-index:-2;
      filter: blur(40px);
    }
    .box:before,
    .box:after {
      background:linear-gradient(235deg,#89ff00,#060c21,#00bcd4);
    }
    .content{
      width: 300px;
      padding: 40px;
      position: absolute;
      top: 50%;
      left: 50%;
      justify-content: center;
      background: #222222;
      text-align: center;
      transform: translate(-50%,-50%);
    }
     .content h1{
       color: white;
       font-weight:500;
    }
    .content input[type="text"], .content input[type="password"] {

      background: none;
      display: block;
      text-align:center;
      border:2px solid #00bcd4;
      margin: 20px auto;
      padding: 14px 20px;
      width: 200px;
      outline: none;
      color:white;
      border-radius:24px;
      -webkit-transition: 0.25s ;
      -moz-transition: 0.25s ;
      -ms-transition: 0.25s ;
      -o-transition: 0.25s ;
      transition: 0.25s ;
    }
    .content input[type="text"]:focus, .content input[type="password"]:focus{
      width: 280px;
      border-color:#89ff00;
    }
    .content input[type="submit"]{
      border: 0;
      background: none;
      display: block;
      text-align:center;
      border:2px solid #00bcd4;
      margin: 20px auto;
      padding: 14px 40px;
      outline: none;
      color:white;
      border-radius:24px;
      -webkit-transition: 0.25s ;
      -moz-transition: 0.25s ;
      -ms-transition: 0.25s ;
      -o-transition: 0.25s ;
      transition: 0.25s ;
      cursor: pointer;
    }
    .content input[type="submit"]:hover {
      background:#89ff00;
      border:2px solid #89ff00;
    }
  </style>
</head>
<body>
<div class="box">
<div class="content">
  <h1>LOGIN</h1>

  <input type="text" placeholder="Username">

  <input type="password" placeholder="Password">

  <input type="submit" value="Login">
</div>
</div>
</body>
</html>
