
### **TERMUX** REPO CLEAN FILES.. <span style="font-size: 23px;">
<span class="Apple-style-span"><b>
<script language="JavaScript" type="text/javascript">
//<![CDATA[
<!--
today = new Date()
if(today.getMinutes() < 10){
pad = "0"}
else
pad = "";
document.write ;if((today.getHours() >=6) && (today.getHours() <=9)){
document.write("BUENOS DIAS!!")
}
if((today.getHours() >=10) && (today.getHours() <=11)){
document.write("COFFEE TIME!!")
}
if((today.getHours() >=12) && (today.getHours() <=17)){
document.write("QUE APROVECHE..")
}
if((today.getHours() >=18) && (today.getHours() <=23)){
document.write("BUENA TARDE..")
}
if((today.getHours() >=0) && (today.getHours() <=3)){
document.write("..BUENAS NOCHES!! ")
}
if((today.getHours() >=4) && (today.getHours() <=5)){
document.write("DUERME BIEN..")
}
// -->
//]]>
</script>
	 [REPO TERMUX](https://yanlimeng.github.io/TERMUX) 
	</b></span></span>



### <marquee><table align="center" width=800 direction=right border="0"><tr><td> :point_right: Hola, bienvenid@......&nbsp;&nbsp; | <strong>&nbsp;&nbsp;**TERMUX** REPO CLEAN FILES....</strong>&nbsp;&nbsp;&nbsp;<i>&nbsp;&nbsp;aqui se prueban herramientas para Termux - Android....&nbsp;</i></td></tr></table></marquee>

<hr>


 ###  [REPO TERMUX](https://yanlimeng.github.io/TERMUX) 



<hr>



- [WeatherForecast](https://yanlimeng.github.io/WeatherForecast.bash/
)

- [printEnviroment](https://yanlimeng.github.io/printEnviroment.bash/
)

- [fortuneQuotes](https://yanlimeng.github.io/fortuneQuotes.bash/
)

- [Figlet](https://yanlimeng.github.io/Figlet-shell/
)

- [Cmatrix](https://yanlimeng.github.io/Cmatrix
)

- [CacaFireScreensaver](https://yanlimeng.github.io/CacaFireScreensaver/
)

- [Teclado Largo](https://yanlimeng.github.io/TecladoLargo.bash/
)



```
 __    _ _____             __ __         
|  |  |_|     |___ ___ ___|  |  |___ ___ 
|  |__| | | | | -_|   | . |_   _| .'|   |
|_____|_|_|_|_|___|_|_|_  | |_| |__,|_|_|
                      |___|              
```

<hr>


<SCRIPT LANGUAGE="JavaScript">
var caution = false
function setCookie(name, value, expires, path, domain, secure) {
var curCookie = name + "=" + escape(value) +
((expires) ? "; expires=" + expires.toGMTString() : "") +
((path) ? "; path=" + path : "") +
((domain) ? "; domain=" + domain : "") +
((secure) ? "; secure" : "")
if (!caution || (name + "=" + escape(value)).length <= 4000)
document.cookie = curCookie
else
if (confirm("La cookie no puede pesar más de 4kb!"))
document.cookie = curCookie
}
function getCookie(name) {
var prefix = name + "="
var cookieStartIndex = document.cookie.indexOf(prefix)
if (cookieStartIndex == -1)
return null
var cookieEndIndex = document.cookie.indexOf(";", cookieStartIndex +
prefix.length)
if (cookieEndIndex == -1)
cookieEndIndex = document.cookie.length
return unescape(document.cookie.substring(cookieStartIndex + prefix.length,
cookieEndIndex))
}
function deleteCookie(name, path, domain) {
if (getCookie(name)) {
document.cookie = name + "=" +
((path) ? "; path=" + path : "") +
((domain) ? "; domain=" + domain : "") +
"; expires=Thu, 01-Jan-70 00:00:01 GMT"
}
}
function fixDate(date) {
var base = new Date(0)
var skew = base.getTime()
if (skew > 0)
date.setTime(date.getTime() - skew)
}
var now = new Date()
fixDate(now)
now.setTime(now.getTime() + 365 * 24 * 60 * 60 * 1000)
var visits = getCookie("counter")
if (!visits)
visits = 1
else
visits = parseInt(visits) + 1
setCookie("counter", visits, now)
document.write("Visita: " + visits)</script>


<html>
<div id="ip4" style="font-size:12px">
<div class='col-md-3'>
<br><br>
<h6 style='color:#ffffff;'>Datos de tu navegador</h6>
<div class="marco2">
<!-- Nombre y version del navegador -->
<script type="text/javascript">
//<![CDATA[
var nVer = navigator.appVersion;
var nAgt = navigator.userAgent;
var browserName  = navigator.appName;
var fullVersion  = ''+parseFloat(navigator.appVersion); 
var majorVersion = parseInt(navigator.appVersion,10);
var nameOffset,verOffset,ix;
if ((verOffset=nAgt.indexOf("MSIE"))!=-1) {
 browserName = "Microsoft Internet Explorer";
 fullVersion = nAgt.substring(verOffset+5);}
else if ((verOffset=nAgt.indexOf("Opera"))!=-1) {
 browserName = "Opera";
 fullVersion = nAgt.substring(verOffset+6);}
else if ((verOffset=nAgt.indexOf("Chrome"))!=-1) {
 browserName = "Chrome";
 fullVersion = nAgt.substring(verOffset+7);}
else if ((verOffset=nAgt.indexOf("Safari"))!=-1) {
 browserName = "Safari";
 fullVersion = nAgt.substring(verOffset+7);}
else if ((verOffset=nAgt.indexOf("Firefox"))!=-1) {
 browserName = "Firefox";
 fullVersion = nAgt.substring(verOffset+8);}
else if ( (nameOffset=nAgt.lastIndexOf(' ')+1) < (verOffset=nAgt.lastIndexOf('/')) ) 
{browserName = nAgt.substring(nameOffset,verOffset);
 fullVersion = nAgt.substring(verOffset+1);
 if (browserName.toLowerCase()==browserName.toUpperCase()) {
  browserName = navigator.appName;}}
if ((ix=fullVersion.indexOf(";"))!=-1) fullVersion=fullVersion.substring(0,ix);
if ((ix=fullVersion.indexOf(" "))!=-1) fullVersion=fullVersion.substring(0,ix);
majorVersion = parseInt(''+fullVersion,10);
if (isNaN(majorVersion)) {
 fullVersion  = ''+parseFloat(navigator.appVersion); 
 majorVersion = parseInt(navigator.appVersion,10);}
document.write('&#10132;  Usas el navegador: '+browserName+', la versión: '+fullVersion);
//]]>
</script><br>
<!-- Hasta aqui nombre y version del navegador -->

  
<!-- Tu agente de usuario es -->
&#10132; Agente:
<script type="text/javascript">document.write(navigator.userAgent);</script><br>
<!-- Hasta aqui Tu agente de usuario es -->

<!-- Medida de la pantalla del navegador web -->
&#10132; Medida de la pantalla del navegador web:
<script type="text/javascript">document.write (document.documentElement.clientWidth,' x ',document.documentElement.clientHeight,' pixeles ');
</script><br>
<!-- Hasta aqui Medida de la pantalla del navegador web -->


<!-- ¿Tu Navegador acepta Cooookies? -->
&#10132; ¿Tu Navegador acepta Cookies?
<script type="text/javascript">
if(navigator.cookieEnabled==true)
cookiesok="Está permitido";else if(navigator.cookieEnabled==false)
cookiesok="Olvidalo";else
cookiesok="Respuesta desconocida";
document.write (cookiesok);
</script><br>
<!-- Hasta aqui ¿Tu Navegador acepta Cooookies? -->

<!-- Â¿Tu Navegador acepta Java? -->
&#10132; ¿Tu Navegador acepta Java?
<script type="text/javascript">
if(navigator.javaEnabled()==true)
javaok="Java está activa";else if(navigator.javaEnabled()==false)
javaok="Java está desactivada";else
javaok="Respuesta desconocida";
document.write (javaok);
</script><br>
<!-- Hasta aqui Â¿Tu Navegador acepta Java? -->

<!-- Pluggins instalados en el navegador -->
&#10132; Pluggins instalados en el navegador:
<a style='color:#ffffff;' href="javascript:pinst();">Ver lista</a><br>
<div id="pl"></div>
<script type="text/javascript">
//<![CDATA[
function pinst(){
if(navigator.appName.indexOf("Microsoft Internet Explorer") != -1){
alert('Lo siento, solo esta disponible esa informaciÃ³n para Firefox y Chrome');}
else{
var num_of_plugins=navigator.plugins.length;
var ventana=window.open('','w','width=400,height=600,left=50,top=50');
for(var i=0;i<num_of_plugins;i++){var list_number=i+1;
ventana.document.write(""+list_number+"- "+navigator.plugins[i].name+"  <br />")}}}
//]]>
</script>
<!-- Hasta aqui Pluggins instalados en el navegador -->
</div>
<br>
</div>
  
  
<div class='col-md-3'>
<h6 style='color:#ffffff;'>Datos de tu equipo</h6>
<div class="marco2">
	
<!-- Ancho de la resoluciÃ³n de tu pantalla -->
&#10132; Ancho de la resolución de tu pantalla: 
<script type="text/javascript">document.write(window.screen.width, " pixeles")
</script><br>
<!-- Hasta aqui Ancho de la resoluciÃ³n de tu pantalla -->

<!-- Altura de la resoluciÃ³n de tu pantalla -->
&#10132; Altura de la resolución de tu pantalla:
<script type="text/javascript">document.write(window.screen.height, " pixeles")
</script><br>
<!-- Hasta aqui Altura de la resoluciÃ³n de tu pantalla -->

<!-- Profundidad del color en Bits -->
&#10132; Profundidad del color en Bits:
<script type="text/javascript">
//<![CDATA[
var colorDepth = window.screen.colorDepth;
if (colorDepth == 4)
	document.write("16 colors");
else if (colorDepth == 8)	
	document.write("256 colors");
else if (colorDepth > 8)
	document.write(colorDepth + " bits");
else
	document.write("Unknown");
//]]>
</script><br>
<!-- Hasta aqui Profundidad del color en Bits -->

<!-- Fecha actual -->
&#10132; Fecha actual:
<script type="text/javascript">document.write (fechahoy());
ahora=new Date();function fechahoy(){var diasemana=new Array('Domingo','Lunes','Martes','MiÃ©rcoles','Jueves','Viernes','SÃ¡bado');var nombremes=new Array('Enero','Febrero','Marzo','Abril','Mayo','Junio','Julio','Agosto','Septiembre','Octubre','Noviembre','Diciembre');var ahora;var fecha=new Date();var ano=fecha.getFullYear();var mes=fecha.getMonth();var dia=fecha.getDay();var num=fecha.getDate();ahora=diasemana[dia]+", "+num+" de "+nombremes[mes]+" de "+ano;return ahora;}
</script><br>
<!-- Hasta aqui Fecha actual -->


<!-- REloj -->
<div id='reloj'></div>	
<!-- //REloj -->

<!-- Tu zona horaria es -->
&#10132; Zona horaria:
<script type="text/javascript">checkTimeZone();
function checkTimeZone(){var rightNow=new Date();var rightNowString=rightNow.toString();var lastColon=rightNowString.lastIndexOf(":");var rightNowZone=rightNowString.substring(lastColon+4,rightNowString.length);var rightNowZone=rightNowZone.replace(/ \d\d\d\d$/,"");var rightNowZone=rightNowZone.replace(/ \d\d\d\d $/,"");var date1=new Date(rightNow.getFullYear(),0,1,0,0,0,0);var date2=new Date(rightNow.getFullYear(),6,1,0,0,0,0);var temp=date1.toGMTString();var date3=new Date(temp.substring(0,temp.lastIndexOf(" ")-1));var temp=date2.toGMTString();var date4=new Date(temp.substring(0,temp.lastIndexOf(" ")-1));var hoursDiffStdTime=(date1-date3)/(1000*60*60);var hoursDiffDaylightTime=(date2-date4)/(1000*60*60);if(hoursDiffDaylightTime==hoursDiffStdTime){document.writeln(rightNowZone+", Horario normal");}else{document.writeln(rightNowZone+", Horario de verano");}}
</script><br>
<!-- Hasta aqui Tu zona horaria es -->

<!-- Sistema operativo -->
&#10132; Sistema operativo:
<script type="text/javascript">
var OSName="Unknown OS";
if (navigator.appVersion.indexOf("Win")!=-1) OSName="Windows";
if (navigator.appVersion.indexOf("Mac")!=-1) OSName="MacOS";
if (navigator.appVersion.indexOf("X11")!=-1) OSName="UNIX";
if (navigator.appVersion.indexOf("Linux")!=-1) OSName="Linux";
document.write(OSName);
</script><br>

<!-- Hasta aqui Sistema operativo -->
</div><br>

<h6 style='color:#ffffff;'>Datos de esta URL</h6>
<div class="marco2"> 
&#10132; Título de la página: <script type="text/javascript">document.write(document.title);</script>
<br>

&#10132; Ultima actualización:
<script type="text/javascript">document.write(document.lastModified);</script><br>
<!--&#10132; DirecciÃ³n URL completa de esta pÃ¡gina:<br>
<script type="text/javascript">document.write(document.URL);</script><br>
&#10132; Nombre del dominio:
<script type="text/javascript">document.write(document.domain);</script><br>-->  


<!-- Historial de navegaciÃ³n en este sitio -->
&#10132; Historial de navegación en este sitio:
<script type="text/javascript">var times=history.length; document.write(+times+' paginas en esta sesión');</script><br>
<!-- Hasta aqui Historial de navegaciÃ³n en este sitio -->
</div><br>
</div>
</div>
</html>
<br>
<br>
<hr>



