
### **TERMUX** REPO CLEAN FILES..

<hr>



### :point_right: [REPO TERMUX](https://yanlimeng.github.io/TERMUX) 



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
