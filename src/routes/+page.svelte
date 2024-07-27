<script>
    import Button from "$lib/components/ui/button/button.svelte";

</script>
<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible " content="IE=edge">
<meta name="viewport" content="width=device-width , initial-scale=1.0">
<link rel="stylesheet" href="style.css"/>
<title>Marel</title>
<style>
   
    
*{
  padding: 0;
margin: 0;
box-sizing: border-box;
font-family: 'Poppins';

}

.container{
  width: 100%;
  height: 100vh;
  background-color:Z ;
  display: flex;
  align-items: center;
  justify-content: center;
}

.container{
  text-align: center;

}

.container h1{
font-size: 100px;
color: #8d1717;
margin-bottom: 50px;
}

.container{
  font-size: 23px;
  color: #772424;
  text-decoration: none;
  border: 2px solid #c61d1d00;
  padding: 15px 25px;
  border-radius: 50px;
transition: 0.33s;
}

.container a:hover{
background-color: #ffffff;
color: #000;
}

.background-clip{
  position: absolute;
  right: 0;
  bottom: 0;
  
  z-index: -1;
}

@media(min-aspect-ratio:16/9){
  .background-clip{
    width: 100%;
    height: auto;
  }
}

@media(max-aspect-ratio:16/9){
  .background-clip{
    width: auto;
    height: 100%;
  }
}
</style>

</head>
<body>

<div class="container ">
    <video src="MV.mp4"  autoplay loop muted  class="background-clip " > 
        <source src="MV.mp4" type="MV.mp4">
    </video>
    <div class="content">
        <h1 class="text-2xl text-red-800">
           MAREL
        
        </h1>
       

        <Button class="">
            <a href="https://www.marvel.com/">official website</a>
        </Button>

    </div>

</div>



</body>

</html>
