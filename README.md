# conversor_brga_210225
<html lang = "en-US" dir="ltrt">
<head>
<meta  charset ="UTF-8" />
<meta name = "description" content= "aplicacion web progresiva para la conversion de la unidades de temperaturas" />
<meta name = "keywords" content = "calculo,matematico,converson,temperatura,practica,investigacion,estudio,converion"/>
<meta name = "autor" content="Brenda Rocio Guzman Arevalo" />
<meta name = "copyright" content= "2025BRGA"/>
<meta name="copyritght" content="2025BRGA" />
<meta name="viewport" content="width=device-widht,initial-scale=1"/>
<title>conversor de temperatura Brenda Guzman</title>
<link rel = "shortcut icon" href ="https://c.s-microsoft.com/favicon.ico?v2" />
<link rel ="stylesheet" href = "css/stlyle.css" />
<link rel= "stylesheet" href = "fontsawesoem-free-6.6.0-web/css/all.css" />
<head>
<body>
<h1> convertidor de temperatura</h1>
<form id = "converter" >
<label for = "input-temp">temperatura:</label>
<input type = "text" id = "input-temp" value = "20" />

<label for = "input-unit"> de </label>
<select id= "input-unit" name ="input-unit">
<option value ="c"> celsius</option>
<option value ="f"> fahrenheit</option>
<option value ="k"> kelvin</option>
</select>
<output name = "output-temp" id="output-temp" for= "input-temp input-unit output-unit">68F</output>
<label for ="output-unit"></label>
</form>
</body>
</html>
