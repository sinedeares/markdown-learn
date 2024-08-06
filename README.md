# Markdown 


**Markdown** - это лёгкий и простой в освоении язык разметки, который позволяет форматировать  текст с помощью нескольких символов. Создан в 2004 году Джоном Грубером и Аароном Шварцем.

------------------------------------
## Где используется Markdown  


* *README* файлы в Системы управления проектами и кодом: **GitHub**, **GitLab** и тп;
* Техническая документация;
* Мессенджеры и соцсети: **Viber**, **Teleegram** и тп;
* Приложения для заметок: **Evernote**, **Medium** и тп;
* Wiki-статьи, базы знаний и так далее.

-----------------------------------------
## Инструменты для работы  


* Редакторы кода, например, VSCode, Sublime, NotePad++ так же поддерживается многими IDE;
* Онлайн редакторы и конвертеры: Dillinger, Editor.m, Typora и другие;
* Библиотеки для различных языков программирования, например:
  * Mistune и MarkDown2 дл Python;
  * Marked и Showdown для JS;
  * Kramdown и Redcarpet для Ruby.

 -----------------------------------------
 ## Почему стоит использовать именно Markdown?  

 
*Markdown* – это не просто еще один язык разметки. Он завоевал огромную популярность благодаря ряду преимуществ, которые делают его идеальным выбором для широкого спектра задач, от написания заметок до создания документации и даже веб-страниц.
Вот почему использовать именно его: 
1. **Простота**: Markdown невероятно прост в изучении и использовании. Он не требует изучения сложных языков программирования или специальных программ. Даже новичок может быстро освоить основные принципы и начать форматировать текст.
2. **Читабельность**: Текст, написанный в Markdown, легко читается как в исходном коде, так и в отформатированном виде. Простые символы, используемые для форматирования, не отвлекают от самого содержания текста, делая его более доступным для восприятия.
3. **Портативность**: Markdown поддерживается большинством редакторов и платформ. Это означает, что вы можете создавать файлы в Markdown на одном устройстве и легко открывать их на другом, не беспокоясь о проблемах с совместимостью.
4. **Сосредоточенность на контенте**: Markdown позволяет сосредоточиться на содержании текста, а не на форматировании. Вы можете писать свои мысли без отвлечения на сложные команды и параметры.
5. **Гибкость**: Markdown можно использовать для широкого спектра задач, от простых заметок до сложных документов и веб-страниц. Существует множество расширений и дополнений, которые позволяют дополнительно настроить Markdown и расширить его возможности.
6. **Совместимость**: Markdown легко преобразуется в другие форматы, такие как HTML, PDF, Word и другие. Это делает его идеальным для обмена файлами и публикации контента на разных платформах.
7. **Удобство совместной работы**: Markdown идеально подходит для совместной работы, так как его легко редактировать и отслеживать изменения в коде.
8. **Открытый стандарт**: Markdown является открытым стандартом, что означает, что он не зависит от какой-либо конкретной компании или продукта. Это гарантирует, что Markdown будет доступен и использовать его будет возможно в будущем.
---------------------------------------------------
 ## Синтаксис языка  

Чтобы сделать **жирный** текст. нужно проставить по два символа \* или \_ до и после текста, который нужно выделить (например, ```**жирный текст**```): 

**слово**  
__слово2__

Для того, чтобы сделать *курсивный* текст. нужно проставить по одному символу \* или \_ до и после текста, который нужно выделить (например, ```*курсивный текст*```): 

*курсив*
_курсив2_

Кроме того, можно совместить два этих стиля, чтобы сделать ___жирный курсивный___ текст, просто сложив соответствующие символы, например, ```___курсивный текст___```:
***жирный курсив***
___жирный курсив 2___

Чтобы сделать текст *зачёкнутым*, достаточно поставить по две "тильды" с двух сторон (```~~Зачёркнутый текст~~```):

~~Что-то зачёркнутое~~

Markdown позволяет выделять *цитаты* в тексте, для этого нужно перед словом поставить символ ">:

>Цитата

*Цитаты* можно делать и *вложенными*, добавляя дополнительный символ ">" (```>>Цитата>>```):
>Это
>Вложенный
>>Блок
>>>>Цитат

Межстрочные *линии* в markdown можно создавать тремы способами: "---", "***", "___" (отображаться они будут одинаково, однако, стоит учитывать, что не все редакторы содержат все три вида кодирования линий):

Первая линия
-----------
Вторая линия
***
Третья линия
___

В markdown можно создавать списки, нумерованные и ненумерованные.  
*Ненумированные* списки создаются одним знаком "+", "-" или "*" в начале строки (так же не везде поддерживаются все 3 вида написания), при том если в первой строке указать, наример ```+ строка ```, а во второй ```* строка 2```, то есть использовать разные знаки, то это будут разные списки.
+ Первый элемент
+ Второй элемент
- Третий жэлемент
* Четвёртый элемент

*Нумерованные* списки делаются через цифру с точкой. При том совершенно неважно, какую цифру указывать во второй строке, всё равно номер строки автоматически будет увеличиваться на единицу. Ниже представлен пример *вложенного списка*, внутренний является нумерованным:
+ Нумерованный 
    1. Первый
    2. Второй

Чтобы *выделить в тексте программный код*, используются тройные обратные кавычки (backtick), например "```print("ok")``"
``` console.log("HELLO"); ```

Если нужно выделить короткий кусок кода, например вызов функции, достаточно одинарной обратной кавычки ("`alert()`"):
`alert()`


*Ссылки* можно вставлять разными способами:
- Ссылка с замещающим текстом ```[Ютуб не пашет](https://www.youtube.com/) ```. [Ютуб не пашет](https://www.youtube.com/);
- Ссылка с замещающим текстом и подсказкой при наведении: ```[Ютуб не пашет](https://www.youtube.com/ "Попытка открыть ютуб")```. [Ютуб не пашет](https://www.youtube.com/ "Попытка открыть ютуб");
- В формате быстрой ссылки: ```<https://www.youtube.com/>``` <https://www.youtube.com/>.

Картинка вставляется похожим образом, нужно только поставить восклицательный знак в начале строки, например: ```![image](https://github.com/user-attachments/assets/f8bbddcb-6a0a-48c8-87b2-53ceb377bcda)``` (так вставлена картинка ниже).

Можно *выделить* текст, слева-справа поставив по 2 знака равенства (``` ==выделенный== ```)
README файл не определяет этот тэг, поэтому приложу скриншот с сайта dillinger:  

![image](https://github.com/user-attachments/assets/f8bbddcb-6a0a-48c8-87b2-53ceb377bcda)

==Выделенный== текст

Можно делать надстрочные и подстрочные индексы, надстрочный - ```т~р~и``` и подстрочный ```т^р^и```. README плохо отображает их:

Т~р~и вниз
Т^р^и вверх

Поэтому так же прилагаю скриншотс  dillinger:
![image](https://github.com/user-attachments/assets/c554641d-555d-42c1-9cc8-a0d25274ae1f)


Markdown
: Облегчённый язык разметки, созданный для обозначения форматирования в простом тексте с максимальным сохранением его читаемости человеком.


Markdown подходит для показа *списка задач*, для этого нужно создать список, а затем перед текстом поставить квадратные скобки, внутри разместив **x**, если задача выполнена (
```
- [ ] Невыполненная задача
- [x] Выполненная задача
- [x] Еще одна выполненная задача
```

Markdown позволяет создавать *таблицы* с помощью вертикальных и горизонтальных палочек. Кроме того, с помощью знака ":" можно выбирать какое выравнивание применять, слева, справа или по центру (в этом случае двоеточие должно быть и слева и справа), например:
```
| Имя             | Фамилия                 | Должность                           |
|:---------------------|:---------------------:|-------------------------------:|
| Иван          | Иванов     | Директор  |
| Смирн          | Смирнов         | Бухгалтер                   |
| Петр  | Петров      | Эффективный менеджер              |
```

Результат:

| Имя             | Фамилия                 | Должность                           |
|:---------------------|:---------------------:|-------------------------------:|
| Иван          | Иванов     | Директор  |
| Смирн          | Смирнов         | Бухгалтер                   |
| Петр  | Петров      | Эффективный менеджер              |

----------------------------------------------------------------------------
### Дополнительная информация  


* [Официальный сайт Markdown](https://daringfireball.net/projects/markdown/)
* [Введение в Markdown](https://ru.markdown.net.br/nachinaya/ "Введение в MarkDown")
* [Markdown на Wikipedia](https://ru.wikipedia.org/wiki/Markdown "Markdown")
* [Использование Markdown в Azure DevOps](https://learn.microsoft.com/ru-ru/azure/devops/project/wiki/markdown-guidance?view=azure-devops "Использование Markdown в Azure DevOps")


