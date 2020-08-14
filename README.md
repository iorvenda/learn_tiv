
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head><script src='https://kit.fontawesome.com/a076d05399.js'></script>
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
    <style media="screen">
    body{
      padding: 0;
      margin: 0;
      height: 812px;
      box-sizing: border-box;
      background-color: #f2f2f2;
      max-width: 375px;
    }
    .main{
      display: grid;
      grid-template-columns: auto;
      width: 375px;
    }
    .module{
      justify-content: center;
      width: 375px;
      height: 300px;
      border-radius: 4px;
      box-shadow: 1px 1px  6px black;
      margin-top: 20px;
      box-sizing: border-box;
      background-color:white;
    }
    .module label{
      color:#66a3ff;
    }.module div button{
      margin-top:10px;

      padding: 20px;
    }.module p{
      font-size: 90%;

    }h2{
       color: #404040;
    }
    .description{
      text-align: center;
    }
      .footer{
        width: 100%;
        margin-top: 100%;
        box-sizing: border-box;
      }
      .upperfooter{
        width: 100%;
        background-color: lightgray;
        box-sizing: border-box;
      }
      .lowerfooter{
        display: grid;
        grid-template-columns: auto auto auto;
        box-sizing: border-box;
      }
    </style>
    <script type="text/javascript">
      function noQ() {
        alert("Notice that there is no Q");
      }
      function phrase() {
        alert("A ya tutu ka u nogh?");
      }
      function greeting()
      {
        alert("U der Ver? as In Good morning!")
      }
    </script>
  </head>
  <body>
 <div class="container">
   <div class="header">
     <label for="">Welcome Iorvenda</label>
   </div>
   <div class="main">
     <div class="module">
       <div class="">
          <label for="">Lession 1</label>
       </div>
       <div class="description">
         <h2>THE ABCs</h2>
         <p>This section will take your through the Tiv letters. </p>
         <p>It is very import to know the pronouciation of them</p>

         <button type="button"  onclick="noQ()"name="button">The Tiv letters</button>
       </div>
     </div>
     <div class="module">
       <div class="">
         <label for="">Lession 2</label>

       </div>
       <div class="">
         <button type="button" onclick="phrase()"name="button">Tiv Popular Phrases</button>
       </div>
     </div>
     <div class="module">
       <div class="">
          <label for="">Lession 3</label>
       </div>
       <div class="">
         <button type="button" onclick="greeting()"name="button">Greetings mates and Elders</button>
       </div>
     </div>
     <div class="module">
       <div class="">
          <label for="">Lession 4</label>

       </div>
       <div class="">
         <button type="button" name="button">Culture, Converstaion with elders</button>
       </div>
     </div>
     <div class="module">
       <div class="">
          <label for="">Lession 5</label>

       </div>
       <div class="">
           <button type="button" name="button">Converstaion with Friends</button>
       </div>
     </div>
     <div class="footer">
       <div class="upperfooter">
         <label for="">Unlock alls courses in Tiv</label>
       </div>
       <div class="lowerfooter">
         <div class="">
        <button type="button" name="button"><i class='fas fa-home' style='font-size:24px'></i></button>
        <p>Home</p>
         </div>
         <div class="">
           <button class="btn active" onclick="gridView()"><i class="fa fa-th-large"></i> Grid</button>
           <p>Courses</p>
         </div>

         <div class="">
   <button type="button" name="button"><i class='fas fa-user-circle' style='font-size:24px'></i></button>
    <p>Profile</p>
         </div>

       </div>
     </div>
   </div>
 </div>
  </body>
</html>
