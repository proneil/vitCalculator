<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>VetsinTech Web Dev Pre-Work Task </title>
</head>
  
  <script>
    //This is a comment
    function calculateFunction(){
      //Get value from first textBox
      var a = document.getElementById("input1id").value;
      
      //Get value from second text box
      var b = document.getElementById("input2id").value;
      
      //Add those two values
      var sum = parseFloat(a) + parseFloat(b);
      
      //Print the result to the page
      document.write(sum);
    }
    
    
    
  </script>
  
  <body>
  
  <h1> Paul's Simple Calculator </h1>
  
  <p> Enter the values in the two text boxes and press the button to see the result </p>
  
  <input type="text" name="input1" id="input1id" />
  +
  <input type="text" name="input2" id="input2id" />
  
  <input type="submit" name"calculateButton" id="calculateButton" 
         onClick="calculateFunction()" value="Calculate Now" />
  
    </br>
  
  <p>  VetsinTech supports our current and returning veterans with re-integration services, and by connecting them to the national technology ecosystem. ViT is committed to bringing together a tech-specific network, resources, and programs for our veterans interested in Education, Entrepreneurship, and Employment - the 3E’s! </p>


</body>
</html>
test to see if this works
ugh
