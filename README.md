### Қайрулла Руслан ВТиП-202
<br>
<img src="screenshots/mobile-phone.jpg" width="20%">
<br>
<br>
<img src="screenshots/0001.png">

```
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>Қайрулла Руслан ВТиП-202 Вариант-6</title>
        </head>

	<body>

<div id="variant">Қайрулла Руслан ВТиП-202 Вариант-6</div>

<!-- Нумерованный текст -->
		<ul type="circle">
			<li>Зима</li>
			<li>Весна</li>
				<ol type=A start="24">
					<li>Март</li>
					<li>Апрель</li>
					<li>Май</li>
				</ol>
			<li>Лето</li>
			<li>Осень</li>
		</ul>
<!-- Код таблицы -->
		<table width="300" border="1">
			<tr height="50">
				<td rowspan="3" style="background-color: red;"></td>
				<td style="background-color: gray; color: white;"></td>
				<td style="background-color: red;"></td>
				<td style="background-color: yellow; color: blue"></td>
				<td style="background-color: green; color: white"></td>
				<td rowspan="3" style="background-color: blue; color: red"></td>
			</tr>
				
			<tr height="50" style="background-color: lime; color: blue">
				<td colspan="4"></td>
			</tr>
			
			<tr height=50>
				<td style="background-color: yellow;color: green"></td>
				<td style="background-color: fuchsia; color: yellow"></td>
				<td style="background-color: silver; color: white"></td>
				<td style="background-color: black; color: red"></td>
			</tr>
		</table>
		<br>
<!-- Поле для ввода текста, по-умолчанию введено "Новосибирск" -->
		<input type="text" value="Новосибирск" size="20">
		<br>
		<br>
<!-- Поле для радиокнопок, выбор один из них, потому что "name" одинаковый,
     по-умолчанию выбрано "Новосибирск" -->
		<input type="radio" name="city">Омск<br>
		<input type="radio" name="city" checked="">Новосибирск<br>
		<input type="radio" name="city">Томск<br>
		<br>
<!-- Поле для ввода пароля, по-умолчанию установлено "123456" -->
		<input type="password" value="123456" size="15">
		<br>
		<br>
<!-- Поле для выбора файла -->
		<input type="file"><br>
		<br>
<!-- Поле для кнопок "отправить" и "сбросить" -->
		<input type="submit" value="Отправить">
		<input type="submit" value="Сбросить">



<!-- ====================================Описание свойств элементов телефона -->	
<style>
#corpus {
    width: 93px;
    height: 182px;
    top: 44px;
    left: 85px;
    right: 0px;
    bottom: 0px;
    background: rgb(214,227,188);
    color: black;
    border-radius: 20px;
    position: relative;
    border-top-width: 1px;
    border-top-style: solid;
    border-right-width: 1px;
    border-right-style: solid;
    border-bottom-width: 1px;
    border-bottom-style: solid;
    border-left-width: 1px;
    border-left-style: solid;
}

#display {
    width: 77px;
    height: 91px;
    background: aqua;
    border-radius: 20px;
    position: relative;
    top: 8px;
    right: 0px;
    bottom: 0px;
    left: 8px;
    border-top-width: 1px;
    border-top-style: solid;
    border-right-width: 1px;
    border-right-style: solid;
    border-bottom-width: 1px;
    border-bottom-style: solid;
    border-left-width: 1px;
    border-left-style: solid;
}

#time {
    width: 72px;
    height: 28px;
    font-family: "Arial";
    font-size: 28px;
    color: blue;    
    position: relative;
    top: 30px;
    right: 0px;
    bottom: 0px;
    left: 2px;
}

#numpad {
    width: 77px;
    height: 75px;
    background: rgb(214,227,188);
    border-radius: 20px;
    position: relative;
    top: 8px;
    right: 0px;
    bottom: 0px;
    left: 8px;
}

#button-left {
    width: 16px;
    height: 16px;
    background: rgb(63,49,81);
    border-radius: 8px;
    position: relative;
    top: 8px;
    right: 0px;
    bottom: 0px;
    left: 8px;
    margin-bottom: 4px;
    border-top-width: 1px;
    border-top-style: solid;
    border-right-width: 1px;
    border-right-style: solid;
    border-bottom-width: 1px;
    border-bottom-style: solid;
    border-left-width: 1px;
    border-left-style: solid;
}

#button-center {
    width: 16px;
    height: 16px;
    background: rgb(63,49,81);
    border-radius: 8px;
    position: relative;
    top: -58px;
    right: 0px;
    bottom: 0px;
    left: 31px;
    margin-bottom: 4px;
    border-top-width: 1px;
    border-top-style: solid;
    border-right-width: 1px;
    border-right-style: solid;
    border-bottom-width: 1px;
    border-bottom-style: solid;
    border-left-width: 1px;
    border-left-style: solid;
}

#button-right {
    width: 16px;
    height: 16px;
    background: rgb(63,49,81);
    border-radius: 8px;
    position: relative;
    top: -124px;
    right: 0px;
    bottom: 0px;
    left: 53px;
    margin-bottom: 4px;
    border-top-width: 1px;
    border-top-style: solid;
    border-right-width: 1px;
    border-right-style: solid;
    border-bottom-width: 1px;
    border-bottom-style: solid;
    border-left-width: 1px;
    border-left-style: solid;
}

/*==========================================описание заголовка "Вариант" */
    #variant {
    color: white;
    font-size: 30px;
    font-style: italic;
    }
    
    body {
    margin-left: 400px;
    background-color: purple;/*цвет фона*/
    color: yellow;/*цвет текста*/
    }
</style>

<!-- ============================Расположение элементов телефона -->

<div id="corpus">
    <!-- ==================================================Экран телефона -->
    <div id="display">
        <!-- ===============================================Часы телефона -->
        <div id="time">12:00</div>
    </div>
    <!-- ==================================================Циферблат телефона -->
    <div id="numpad">
       <!-- ==========================================Кнопочки из левого столбца -->
       <div id="button-left"></div>
       <div id="button-left"></div>
       <div id="button-left"></div>

       <!-- ====================================Кнопочки из центрального столбца -->
       <div id="button-center"></div>
       <div id="button-center"></div>
       <div id="button-center"></div>

       <!-- ====================================Кнопочки из правого столбца -->
       <div id="button-right"></div>
       <div id="button-right"></div>
       <div id="button-right"></div>
    </div>
</div>
</body>
</html>
```
