# quilt_maker
Web Dev 1.7.7 Make a Quilt Challenge
<!DOCTYPE html>
<html>
	<head>
		<style>
		    html,body{
		        display:flex;
		        flex-wrap: wrap;
		        height:100%;
		        width:100%;
		        padding-left:2%;
		        padding-right:2%;
		    }
		    div{
		        height:10%;
		        width:9%;
		        border: 1px solid black;
		    }
		</style>
	</head>
	<body>
	    <div id="colors">
	      <div class="div1" mouseover="Paint"></div>  
	       <div class="div2" mouseover= "Paint"></div>
	        <div class="div3" mouseover= "Paint"></div>  
	         <div class="div4" mouseover= "Paint"></div> 
	   </div>
		<script>
		    //1. add 100 divs to the canvas
		    //2. append them to document.body
		    //3. hoover mouse over div, to change to one of four colors
		    //4. use onmouseover or mouseover
		    //5. create function paint to generate random color
		    //6. set background color of div to that color
		    //write function paint 
		    
		    var div = document.getElementsById("colors");
		        for (var i = 0; i < 100; i++);
		        div[i].addEventListener("mouseover", randomColor)
		        
		        document.body.appendChild(div);
		        
		    
		    
		    function paint(){
		         randomColor.style.backgroundColor = "#00FF00"
		        randomColor.style.backgroundColor = "#0000FF"
		        randomColor.style.backgroundColor = "#800080"
		        randomColor.style.backgroundColor = "#0D98BA"
		        
		    console.log(Math.floor(Math.random() * 4));
		      
		    }
		</script>
	</body>
</html>
