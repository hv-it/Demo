# Demo
Demo project
Dit zijn de eerste aanpassing aan het readme.md bestand
Deze staat in de readme-edit branche

-------------- Even wat extra test data --------------------------------
<!DOCTYPE html>
<html>
<body>

<p>Datum functie</p>

<button onclick="myFunction()">Druk knop voor de datum</button>

<p id="demo"></p>
<p id="demo2"></p>


<script>
function myFunction() {
    var d = new Date();
    var jaar = d.getFullYear();
    var maand=d.getMonth();
    var dag=d.getUTCDate();
    
    document.getElementById("demo").innerHTML =dag+"-"+maand+"-" + jaar;

	dag = dag+1
  	document.getElementById("demo2").innerHTML =dag+"-"+maand+"-" + jaar;


}
</script>

</body>
</html>
