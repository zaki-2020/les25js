<html>
<head>
<meta charset="utf-8">
<title>Mijn webpagina</title>
<script
src="http://code.jquery.com/jquery-3.1.0.min.js"> </script>
<script type="text/javascript">
$(document).ready(function() {
$("#knop").click(function() {
var naam = $("#idTekstveld01").val();
var achternaam = $("#idTekstveld001").val();
var jaar = $("#idTekstveld011").val();
var dhl = $("#idTekstveld021").val();
var boek = $("#idTekstveld2").val();
var film = $("#idTekstveld3").val();
window.alert(
"Ik ben " + naam +
" mijn achternaam is " + achternaam +
" Ik ben " + jaar +
" Ik werk bij " + dhl +
" en mijn favoriete boek is " + boek +
" en mijn favoriete film is " + film );
});
});
</script>
</head>
<body>
<form>
Wat is uw naam?
<input type="text" id="idTekstveld01"><br><br>
Wat is uw achternaam?
<input type="text" id="idTekstveld001"><br><br>
Hoe oud bent u?
<input type="text" id="idTekstveld011"><br><br>
Wat voor werk doet u?
<input type="text" id="idTekstveld021"><br><br>
Wat is uw favoriete boek?
<input type="text" id="idTekstveld2"><br><br>
Wat is uw favoriete film?
<input type="text" id="idTekstveld3"><br><br>
<input id="knop" name="knop" type="button"
value="Klik op deze knop">
</form>
</body>
</html>
