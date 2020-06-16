# Methods
метод getElement и свойство .innerHTML
<!DOCTYPE html>
<html>
<head>
	<title>Методы</title>
		<script type="text/javascript">
			function addItem() {
			document.getElementById("container").innerHTML = "Элемент для добавления";
			}
		</script>
</head>
<body>
	<input type="button" name="button" value="Добавить элемент" onclick="addItem();">
	<div id="container">
	</div>
</body>
</html>
