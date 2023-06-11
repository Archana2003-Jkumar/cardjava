# Birthdaycard-java
## Aim :
To create a website for birthday card using htmland css.
## Code:
```
<!DOCTYPE html>
<html>
  <head>
    <title>Hi!</title>
  </head>
  <style>
    body, html {
	  height: 100%;
	  margin: 0;
	}
    .container {
	  height: 100%;
	}
    p{
            font-size: 45px;
            padding-top: 3%;
			margin: 0;
            font-family:Georgia, 'Times New Roman', Times, serif;
            font-weight: 800;
            color:yellowgreen;
		}
    marquee{
        font-size: 45px;
            padding-top: 2%;
			margin: 0;
            font-family:Georgia, 'Times New Roman', Times, serif;
            font-weight: 800;
            color: rgb(11, 95, 128);
        }

  .centered-image {
    position: absolute;
    top: 60%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
  .bg {
      height: 150%;
	  background-position: center;
	  background-size: cover;
	  
   }
  .image1 {
	  background-image: url("./c2.png");
	}
  #left {  
    display: inline;
float: left;  
}  
#right {  
  display: inline;
float: right;  
} 
.cnt{
  padding-left: 5cm;
}
  </style>
  <body>
    <div class="container">
        <div class="bg image1">
            <marquee>BE HAPPY AND KEEP ROCKING</marquee>
            <div style="display: inline;">
              <p align="center" style="padding-left: 2cm;">HAPPY BIRTHDAY!!</p>  
              <img id="right" src="./bal.webp" style="height: 400px; width: 300px; padding-top: 2cm;"> 
              <img  src="./c4.jpg" style="text-align: center; height: 250px; width: 500px; padding-left: 12cm;">
              
              <img id="left" src="./bal.webp" style="height: 400px; width: 300px; padding-top: 2cm;"> 
              <p align="center" style="padding-left: 3cm;">May this day be a glorious day !!!</p>
            
            
            </div>               
        
  </body>
</html>
```
## Output:
![image](https://github.com/Archana2003-Jkumar/cardjava/assets/93427594/c9f7ae03-a55d-46ff-a8ec-e614e854bfd9)
## Result:
Thus the program has been successfully completed.
