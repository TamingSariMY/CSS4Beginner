<p align="center">
  <img src="https://github.com/TapauServer/CSS4Beginner/blob/main/assets/css-logo.png" width="250" height="300" />
</p>

#
# What is CSS?
* CSS: Cascading Style Sheet
* CSS is a language used to design or beautify web pages

#
# The difference between inline, internal and external

#### Inline: placed inside an HTML element as an attribute
#### Internal: Placed in the HTML <head>, within the <style> element
#### External: Written in a separate file with HTML. Called by HTML using the <link> element
  
#
### Element: Applies to HTML elements
```python
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Element</title>
	<style type="text/css">
		
		body {
			background: black;
		}
		h1 {
			color: blue;
		}

		p {
			color: red;
			font-size: 300%;
		}

	</style>
</head>
<body>
	<h1>Contoh selector Element</h1>
	<p>hanya boleh dipanggil sekali</p>
</body>
</html>
```
  
### Class: Applied to class attributes and can be called more than once
```python
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Class</title>
	<style type="text/css">
		
		body {
			background: black;
		}

		.biru {
			color: darkblue;
		}
		.merah {
			color: darkred;
		}
		.cyan {
			color: darkcyan;
		}
		.besar {
			font-size: 200%;
		}
		.besarsangat {
			font-size: 300%;
		}

	</style>
</head>
<body>

	<h1 class="biru">Contoh selector class</h1>
	<p class="merah besarsangat">boleh dipanggil banyak kali</p>

	<h1 class="merah">Contoh selector class</h1>
	<p class="cyan besar">boleh dipanggil banyak kali</p>

</body>
</html>
```
  
### ID: Applied to a specific part and only called once
```python
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>ID</title>
	<style type="text/css">
		
		body {
			background: cyan;
		}
	
		#hijaukuning {
			color: greenyellow; font-size: 300%;
		}

	</style>
</head>
<body>
	<h1>Contoh selector ID</h1>
	<p id="hijaukuning">hanya boleh dipanggil sekali</p>
</body>
</html>
```






























