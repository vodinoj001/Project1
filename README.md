<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>Задание 1</title>
	</head>
	<body>
		<h1>Задание 1</h1>
		<ol>
			<li><a href="http://moodle.kubsu.ru/">example.com</a></li>
			<li><a href="https://moodle.kubsu.ru/">example.comc с протоколом https</a></li>
			<li><a href = "ftp://ivanov:123456@ftp.anyhost.ru/">Ссылка на файл на сервере FTP без авторизации</a></li>
			<li><a href = ""ftp://example:1234@example.com/exec.txt"">C авторизацией</a></li>
			<li><a id = "anchor" href = "https://moodle.kubsu.ru/course/view.php?id=780#anchor">Cсылка на фрагмент страницы некоторого сайта</a></li>
			<li><a id = "top" href = "#top">Наверх</a></li> 
			<li><a href = "https://www.google.com/webhp?hl=ru&sa=X">Cсылка с двумя параметрами в URL</a></li>
			<li><a href = "https://moodle.kubsu.ru/" title = "Главное меню">https://moodle.kubsu.ru/ </a><br>
				<a href = "https://moodle.kubsu.ru/course/index.php?categoryid=12" title = "Факультет Компьютерных технологий и прикладной математики">https://moodle.kubsu.ru/course/index.php?categoryid=12</a><br>
				<a href = "https://moodle.kubsu.ru/course/view.php?id=780" title = "Разработка пользовательского Web-интерфейса">https://moodle.kubsu.ru/course/view.php?id=780</a></li>
			<li><a title="без href">без href</a></li>
			<li><a href = ""> Ссылка с пустым href</a></li>
			<li><a href="https://example.com/" rel="nofollow">Ссылка, по которой запрещен переход поисковикам</a></li>
			<li><a href="http://example.com/"><noindex>Ссылка, запрещенная для индексации поисковиками</noindex></a></li>
			<li><p>В Новой Зеландии нашли окаменелости гигантского длинноногого пингвина<a href = https://nauka.tass.ru/nauka/12422931> Journal of Vertebrate Paleontology.</a></li>
			<li><a href = "https://moodle.kubsu.ru/"><img src = "image.jpg" width="200"></a></li>
			<li><img src="2640804.jpg"width="200" usemap="#figure">
			<map name="figure">
				<area shape ="rect" coords= "25,25,125,125" href="https://en.wikipedia.org/wiki/Circle">
				<area shape= "circle" coords = "150,75,50" href="https://en.wikipedia.org/wiki/Square">
			</map>
			</li>
			<li><a href="/about">Относительная ссылка на страницу в текущем каталоге</a></li>
			<li><a href="/about/contacts">  Относительная ссылка в каталоге about  </a> </li>
			<li><a href="../page.html">  Относительная в каталоге уровнем выше текущего  </a></li>
			<li><a href="../../page.html">  Относительная в каталоге уровнем выше текущего  </a></li>
			<li><a href="https://vk.cc/c5SIn1">Сокращенная ссылка на главную страницу moodle.kubsu.ru</a></li>
			<li><a href="https://vk.cc/c5SIoy">Сокращенная ссылка на внутреннюю страницу moodle.kubsu.ru</a></li>	
		</ol>
		<h1>Форма</h1>

		<form action="/"
			method="POST">

      <label>
        Введите имя:<br />
        <input name="field-name-1"
          value="" />
      </label><br />

      <label>
        Текстовое поле email:<br />
        <input name="field-email"
          value=""
          type="email" />
      </label><br />

      <label>
        Дата рождения:<br />
        <input name="field-date"
          value="07.01.2002"
          type="date" />
      </label><br />
		Пол : <br />
      <label><input type="radio" checked="checked"
        name="radio-group-1" value="Значение1" />
        Мужской</label>
      <label><input type="radio"
        name="radio-group-1" value="Значение2" />
        Женский</label><br />
		Количество конечностей : <br />
      <label><input type="radio" checked="checked"
        name="radio-group-2" value="Значение1" />
        4</label>
      <label><input type="radio"
        name="radio-group-2" value="Значение2" />
        6</label><br />
        

		<label>

		<label>
        Сверхспособности :
        <br />
        <select name="field-name-4[]"
          multiple="multiple">
          <option value="Значение1">Бессмертие</option>
          <option value="Значение2" selected="selected">Прохождение сквозь стены</option>
          <option value="Значение3" selected="selected">Левитация</option>
        </select>
      </label><br />
		<label>
        Биография :<br />
        <textarea name="field-name-2">:)</textarea>
      </label><br />

      

      С контрактом ознакомлен(а) :<br />
      <label><input type="checkbox" checked="checked"
        name="check-1" />
         </label><br />

      
      <input type="submit" value="Отправить" />
		</form>

	</body>
	
</html>
