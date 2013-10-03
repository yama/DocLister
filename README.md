### DocLister for MODX Evolution
Класс для вывода информации из таблиц по предопределенным правилам.
Если нет правил, то данные отображаются без дополнительной обработки и связи. Т.е. все поля и значения совпадают с базой данных.

Правила для обработки информации описаны в контроллерах.
Главный контроллер - **site_content** который определяет связь основных документов site_content с данными в TV-параметрах

На базе класса DocLister сформировано 2 сниппета:
* **DocLister** - основной сниппет для вывода информации по принципу сниппетов Ditto и CatalogView
* **DLcrumbs** - для формирования хлебных крошек по принципу сниппета Breadcrumbs.

### Полезные ссылки
---------
* **Обзор**: http://blog.agel-nash.ru/2013/9/doclister.html
* **Документация**: http://blog.agel-nash.ru/addon/doclister.html
* **Пример работы**: http://doclister.agelnash.ru

### Автор
---------
<table>
  <tr>
    <td><img src="http://www.gravatar.com/avatar/bf12d44182c98288015f65c9861903aa?s=60"></td><td valign="middle">Борисов Евгений<br>Agel Nash<br><a href="http://artdevue.com">http://agel-nash.ru</a></td>
  </tr>
</table>

### Thanks
* @[kabachello](https://github.com/kabachello)
* @[Pathologic](https://github.com/Pathologic)