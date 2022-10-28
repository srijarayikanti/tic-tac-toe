<html>
<head>
  <title>tictactoe</title>
  <style>
    h1{
      text-align:center;
    }
    *
    {
      background-color:lavender;
    }
    table tr,th,td{
            background-color:pink;
        }
    table.center {
          margin-left: auto; 
          margin-right: auto;
       }
  </style>
 <body>
   <h1 style="color:brown">TIC TAC TOE</h1>
   <h1 style="color:blue"><b>Welcome to the world of tic tac toe<b></h1>
   <h1 style="color:purple"><b>Player one will start with "x" and player two will start with "0"<b></h1><br>
  <table class="center">
   <tr>
      <td>
      <input type="text" id="a" onclick="fun1();logic();">
      <input type="text" id="b" onclick="fun2();logic();">
       <input type="text" id="c" onclick="fun3();logic();">
      </td>
    </tr><br>
     <tr>
      <td>
      <input type="text" id="d" onclick="fun4();logic();">
      <input type="text" id="e" onclick="fun5();logic();">
       <input type="text" id="f" onclick="fun6();logic();">
      </td>
    </tr>
     <tr>
      <td>
      <input type="text" id="g" onclick="fun7();logic();">
      <input type="text" id="h" onclick="fun8();logic();">
       <input type="text" id="i" onclick="fun9();logic();">
      </td>
    </tr>
   </table>
  <script>
       flag=1;
      function fun1()
         {
            if(flag==1){
               document.getElementById("a").value="x";
               flag=0;}
           else {            
               document.getElementById("a").value="0";
               flag=1;   
            }    
       }
      function fun2()
         {
            if(flag==1){
               document.getElementById("b").value="x";
               flag=0;}
           else{              
               document.getElementById("b").value="0";
               flag=1;  
            }      
       }
      
      function fun3()
         {
            if(flag==1){
               document.getElementById("c").value="x";
               flag=0;}
           else
              {
               document.getElementById("c").value="0";
               flag=1;
         }
       }
       function fun4()
         {
            if(flag==1){
               document.getElementById("d").value="x";
               flag=0;}
           else
             { 
               document.getElementById("d").value="0";
               flag=1;
         }
       }
     function fun5()
         {
            if(flag==1){
               document.getElementById("e").value="x";
               flag=0;}
           else {             
               document.getElementById("e").value="0";
               flag=1; 
            }        
       }
     function fun6()
         {
            if(flag==1){
               document.getElementById("f").value="x";
               flag=0;}
           else   {         
               document.getElementById("f").value="0";
               flag=1;  
            }    
       }
    function fun7()
         {
            if(flag==1){
               document.getElementById("g").value="x";
               flag=0;}
           else    {          
               document.getElementById("g").value="0";
               flag=1;
         }
       }
     function fun8()
         {
            if(flag==1){
               document.getElementById("h").value="x";
               flag=0;}
           else{
               document.getElementById("h").value="0";
               flag=1;
            }       
       }
      function fun9()
         {
            if(flag==1){
               document.getElementById("i").value="x";
               flag=0;}
           else{
               document.getElementById("i").value="0";
               flag=1;  
           }       
       }
     function logic()
        {
              one=document.getElementById("a").value; 
              two=document.getElementById("b").value; 
            three=document.getElementById("c").value;
              four=document.getElementById("d").value;
             five=document.getElementById("e").value;
             six=document.getElementById("f").value;
             seven=document.getElementById("g").value;
             eight=document.getElementById("h").value;
             nine=document.getElementById("i").value; 
        
       if(one=="x"&&two=="x"&&three=="x")
         {
            alert("x won");
         }
        else if(one=="0"&&two=="0"&&three=="0")
         {
           alert("0 won");
         }
       else if(four=="x"&&five=="x"&&six=="x")
         {
           alert("x won");
         }
       else if(four=="0"&&five=="0"&&six=="0")
         {
           alert("0 won");
         }
        else if(seven=="x"&&eight=="x"&&nine=="x")
         {
           alert("x won");
         }
        else if(seven=="0"&&eight=="0"&&nine=="0")
         {
           alert("0 won");
         }
      else if(one=="x"&&five=="x"&&nine=="x")
          {
             alert("x won");
          }
       else if(one=="0"&&five=="0"&&nine=="0")
          {
             alert("0 won");
          }
     else if(three=="x"&&five=="x"&&seven=="x")
          {
             alert("x won");
          }
      else if(three=="0"&&five=="0"&&seven=="0")
          {
             alert("0 won");
          }
      else if(one=="x"&&four=="x"&&seven=="x")
         {
            alert("x won");
         }
       else if(one=="0"&&four=="0"&&seven=="0")
         {
            alert("0 won");
         } 
       else if(two=="x"&&five=="x"&&eight=="x")
         {
            alert("x won");
         } 
       else if(two=="0"&&five=="0"&&eight=="0")
         {
            alert("0 won");
         } 
       else if(three=="x"&&six=="x"&&nine=="x")
         {
            alert("x won");
         } 
        else if(three=="0"&&six=="0"&&nine=="0")
         {
            alert("0 won");
         } 
   }
     </script>
</body>
</head>
</html>
   
