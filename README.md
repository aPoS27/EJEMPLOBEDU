# EJEMPLOBEDU
<!DOCTYPE html>
<html lang="es">
<head>
</head>
<body>
<h1>Dos formas de mostrar la fecha</h1>
<script>
var date=new Date();var d=date.getDate();var day=(d<10)?'0'+d:d;var m=date.getMonth()+1;var month=(m<10)?'0'+m:m;var yy=date.getYear();var year=(yy<1000)?yy+1900:yy;document.write(day+"/"+month+"/"+year);
</script><br>
<script>
function makeArray(){for(i=0;i<makeArray.arguments.length;i++)this[i+1]=makeArray.arguments[i]}var months=new makeArray('Enero','Febrero','Marzo','Abril','Mayo','Junio','Julio','Agosto','Septiembre','Octubre','Noviembre','Diciembre');var date=new Date();var day=date.getDate();var month=date.getMonth()+1;var yy=date.getYear();var year=(yy<1000)?yy+1900:yy;document.write("Hoy es "+day+ " de "+months[month]+" del "+year);
</script>
</body>
</html>    