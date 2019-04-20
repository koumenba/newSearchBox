<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>search</title>
  <style>
    body {
      margin:0;
      padding:0;
      background:#cb7575;
    }
    .search {

      position: absolute;
      top: 43%;
      left: 35%;
      justify-content: center;
      background:#ef9e9f ;
      text-align: center;
      width: 90px;
      height: 90px;
      border-radius: 45px;
      -webkit-box-shadow: 5px 5px 20px #f1bbba ,-5px -5px 20px #f1bbba;
      -moz-box-shadow: 5px 5px 20px #f1bbba ,-5px -5px 20px #f1bbba;
      box-shadow: 5px 5px 20px #f1bbba ,-5px -5px 20px #f1bbba ;
    }
    .search input {
      display:none;
    }
    .search img {
      width: 70px;
      height:70px;
      padding:10px;
    }
    .search:hover {
      width: 500px;
      height:90px;
      border-radius:40px;
      display: flex;
      justify-content: flex-start;
    }
    .search:hover img {
      display: inline-block;
    }
    .search:hover input {
      display: inline-block;
      background:#ef9e9f ;
      outline: none;
      font-size: 20px;
      color: white;
      width:400px ;
      height:89px;
      padding:0;
      border:0;
      border-radius: 40px;
    }
  </style>
</head>
<body>

<div class="search">
  <a href="http://baidu.com"><img src="img/search.png"></a>
  <input type="text" placeholder="">
</div>

</body>
</html>
