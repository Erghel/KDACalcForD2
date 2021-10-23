# KDA Calculator For Dota 2
Очень простой онлайн калькулятор для подсчета КДА[KDA] (Kill Death Assists) в Доте (возможно в будущем будут еще какие-то изменения, но пока нет) 

Скрипт для страницы написан на [YoptaScript](https://github.com/samgozman/YoptaScript), но для удобства здесь выложен ориганльный JavaScript код. 

 JS код:
```cs
function func(){
var num1 = Number(document.getElementById("num1").value);
var num2 = Number(document.getElementById("num2").value);
var num3 = Number(document.getElementById("num3").value);
var result = (num1 + num2) / num3 ;

document.getElementById("result").innerHTML = result;
}
```
# Команда 
```
Frontend + Script = Erghel 

Тестирование + фидбек = Etherus, Gr1zLy, mindframe
```
