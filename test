<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        
        
        .sl {
            display: inline-block;
            height: 15px;
            width: 15px; 
            border: 1px solid rgb(17, 13, 13);
            margin-right: 20px;
        }
        div {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>小学加法</h1>
    <div >
        <span><input type="text" id="num1"></span>
        <span>+</span>
        <span><input type="text" id="num2"></span>
    </div>
    <div>
        A.<span  > <input type="button" class="sl" id="as1" ></span>
        B.<span  ><input type="button" class="sl" id="as2"></span>
        C.<span  ><input type="button" class="sl" id="as3"></span>
        D.<span  ><input type="button" class="sl" ></span>
    </div>
    <script>
        document.getElementById("as1").value = parseInt(Math.random() * 20);
        document.getElementById("as2").value = parseInt(Math.random() * 20);
        document.getElementById("as3").value = parseInt(Math.random() * 20);
        
        document.getElementById("num1").value = parseInt(Math.random() * 10);
        document.getElementById("num2").value = parseInt(Math.random() * 10);
        function getRand(){
          var  num1 = document.getElementById("num1").value;
          var  num2 = document.getElementById("num2").value;
          
            var result = document.getElementById(("num1").value+("num2").value);
            document.getElementById("as4").value = parseInt(result);
            var rel = this.value;
            
            if(result === rel){
                alert("选对了!")
            }
            else{
                alert("选错了")
            }
        }
        
    </script>    
    
</body>
</html>
