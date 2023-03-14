# lecture_52_JS_Forms_controls_Properties_and_Methods  

#  [Задачи ](https://github.com/schoolteacherMP/lecture_52_JS_Forms_controls_Properties_and_Methods/blob/main/tasks.md)  

Свойства для навигации по формам:  

**document.forms**  
Форма доступна через `document.forms[name/index]`.  

**form.elements**  
Элементы формы доступны через `form.elements[name/index]`, или можно просто использовать `form[name/index]`. Свойство `elements` также работает для `<fieldset>`.  

**element.form**  
Элементы хранят ссылку на свою форму в свойстве `form`.  

Значения элементов формы доступны через `input.value`, `textarea.value`, `select.value` и т.д. либо `input.checked` для чекбоксов и переключателей.  

Для элемента `<select>` мы также можем получить индекс выбранного пункта через `select.selectedIndex`, либо используя коллекцию пунктов `select.options`.  
