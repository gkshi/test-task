### Тестовое задание
#### на позицию "Front-end developer (Junior/Middle, Vue.js)" в Lebedev Studio


&nbsp;
![](https://cdn-images-1.medium.com/max/1200/1*-8AAdexfOAK9R-AIha_PBQ.png)
&nbsp;


#### Цель
Разработать SPA-приложение с использованием `Vue` + `Vuex` + `Vue router`.  
Приложение должно получать данные из API и выводить их в клиентскую часть.  
API: [https://dog.ceo/dog-api](https://dog.ceo/dog-api)

&nbsp;

#### Меню
Меню должно отображаться вверху на всех страницах и состоять из пунктов:  
1. Главная
2. Порода (селект с выбором породы)
3. Избранное

Навигация по этим пунктам должна осуществляться с помощью `vue-router`.

&nbsp;

### Главная страница
* Отображает список изображений всех собак
* В шапке должен быть селект позволяющий отфильтровать изображения по породе.
* По стандарту должно отображаться 20 изображений и реализован бесконечный скролл с подгрузкой следующих 20 изображений.

&nbsp;

### Страницы пород
При выборе определенной породы в селекте происходит роутинг на **app.ru/{breed}**, например app.ru/husky.  
При переходе по таким урлам должны загрузиться изображения только конкретной породы.

&nbsp;

### Избранное
Каждое изображение можно лайкнуть (иконка сердца), после чего эти изображения можно будет увидеть на странице **app.ru/favourites**. Информация о лайкнутых фото должна храниться в localStorage.

&nbsp;

### Общие требования
* Проект должен быть выполнен на основе скелета [https://github.com/vuejs-templates/webpack](https://github.com/vuejs-templates/webpack)
* Использование ESLint standard
* Вся логика работы с API (эндпоинты) находится во Vuex
* Допустимые к использованию библиотеки только vue, vuex, vue-router, axios
* JS-код на синтаксисе ES6+
* Дизайн приложения на свое усмотрение (без использования css фреймворков)
* Исходный код проекта должен быть выложен на GitHub.

&nbsp;

![](https://media.giphy.com/media/pDgHg2Lcju3Ty/giphy.gif)
