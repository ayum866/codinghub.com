<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            background-color:black;
        }
    .login1{
        height: 400px;
        width: 400px;
        background: linear-gradient(skyblue,blue,darkblue);
        animation: login1 2.5s forwards;
        margin: auto;
        align-content: center;
     }
     @keyframes login1 {
        from{
            border: 2px solid red;
            background: linear-gradient(skyblue,blue,darkblue);
        }
        to{
            border: 10px solid blue;
            border-radius: 100%;
            background:red;
        }
     }

  #h1{
            color: transparent;
            text-align: center;
            animation: n 2.5s forwards;
            font-size: xx-small;
        }
        @keyframes n{
            from{
                color: transparent;
                transform: rotate(0deg);
                font-size: xx-large ;
               
  }
            to{
                color:blue;
                transform:rotate(360deg);
                font-size: 60px;
                
  }
        }
        button{
            height: 35px;
            width: 200px;
            background: linear-gradient(skyblue,blue,darkblue);
            color: rgb(255, 221, 0);
            font-weight: bold;
            border: 1px  rgb(255, 221, 0);
        }
        button:hover{
            height: 35px;
            width: 200px;
            background: rgb(255, 221, 0);
            color: darkblue;
            font-weight: bold;
            border: 1px darkblue;
        }
    

  .lo{
            height: 40px;
            width: 220px;
            margin: auto;
        }
        p{
            color:red;
            animation: lp 2s infinite alternate;
   }
        @keyframes lp{
            0%{color: red;}
            10%{color: orangered;}
            20%{color:orange;}
            30%{color:yellow;}
            40%{color:lawngreen;}
            50%{color:lightgreen;}
            60%{color:darkgreen;}
            70%{color:skyblue;}
            80%{color:blue;}
            90%{color:purple;}
            100%{color:rgb(153, 37, 56);}
        }
    </style>
</head>
<body>
    <p id="clock"></p>

<script>
  setInterval(() => {
    const now = new Date();
    document.getElementById("clock").textContent = now.toLocaleTimeString();
  }, 1000);
</script>

<div class="login1"><h1 id="h1">CODING HUB</h1></div>
<br>
<div class="lo">
<a href="L2.html"><button type="button">LOGIN</button></a>
<br><br>
<a href="L3 reg.html"><button type="button">REGISTER</button></a>
</div>
</body>
</html>
