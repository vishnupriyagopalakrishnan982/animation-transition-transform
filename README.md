# animation-transition-transform
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
  <style>
        div{
        background-color:greenyellow;
        height: 100px;
        transition: width 4s, height 4s, background-color 5s;
        }
        div:hover{
            width: 400px;
            height: 400px;
            background-color: aqua;
            transform: rotate(360deg);
        }
        main{
            background-color: blue;
            height: 450px;
            width: 100px;
            animation: Hello 14s;
            
        }
        @keyframes Hello{
            20%{
                background-color: green;
            }
            40%{
                background-color: blue;
            }
            80%{
                background-color: indigo;
            }
            100%{
                background-color: black;
            }
        }
        section{
            background-image: url("https://www.pexels.com/photo/two-yellow-labrador-retriever-puppies-1108099/");
            height: 500px;
            width: 100px;
            animation: hi 14s infinite;
        }
        @keyframes hi{
            40%{
                background-image: url("https://www.pexels.com/photo/two-yellow-labrador-retriever-puppies-1108099/");
            
            }
            60%{
                background-image: url('https://www.pexels.com/photo/two-yellow-labrador-retriever-puppies-1108099/');
            }
            80%{
                background-image: url("https://www.pexels.com/photo/two-yellow-labrador-retriever-puppies-1108099/");
            } 
            100%{
                background-image: url("https://www.pexels.com/photo/two-yellow-labrador-retriever-puppies-1108099/");
            } 
            
        }


   </style>
</head>
<body>
    <div><main>
    </main></div>
    <br><br><br>
    
</body>
</html>
      
