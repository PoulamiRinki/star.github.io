<!DOCTYPE html>
<html lang="en"> 
    <head> 
        <meta charset="UTF-8" />
         <meta http-equiv="X-UA-Compatible" content="IE=edge" /> 
         <meta name="viewport" content="width=device-width, initial-scale=1.0" />
         <title> Star Pattern </title>
         </head>
         <body>
             <script>
                 let n = prompt("Enter A Number For Generate  Pattern And Open Comsole");
                 let stars = "";
                 for( let i = 1; i<=n; i++){
                 for(let j = 1; j<=n-i; j++){
                 stars+="&nbsp;"
                 }
                 for(let k =0; k < 2*i - 1; k++){
                     stars +="*";
                 }
                 stars += "</br>";
                }
                document.write(stars);
                console.log(stars);
                

             </script>
         </body>
         </html>
