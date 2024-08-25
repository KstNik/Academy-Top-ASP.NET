# Academy-Top-ASP.NET

#### Экзаменационная работа

## ExaminationWork

Создать веб-проект «Писательская платформа».    
Основная задача проекта: предоставить удобный интерфейс для публикации произведений начинающих писателей, а также дать возможность пользователям комфортно читать опубликованные произведения.    
Необходимо хранить информацию о:
- пользователях (логин, пароль, e-mail);
- произведениях (название, жанр (фантастика, детектив, триллер, история и т.д.), дате публикации, рейтинге (от 0 до 100));
- комментариях пользователей к произведениям.    
Проект должен позволять:    
- регистрироваться новым пользователям;
- изменять свои данные существующим пользователям;
- пользователям удалить свой аккаунт из системы. Если пользователь удалил свой аккаунт, все его комментарии и опубликованные произведения должны остаться на «Писательской платформе»;
- зарегистрированному пользователю опубликовать свое произведение;
- пользователю прочесть выбранное произведение. При отображении произведения в браузере необходимо разбивать его на страницы, если этого требует объем произведения;
- выставить рейтингу произведению;
- написать комментарий к произведению;
- искать произведения по автору, названию, жанру;
- сортировать Топ-50 произведений по жанру, оценкам, комментариям.

#### Решения домашних заданий

## Homework 01

### Тема: "Внедрение зависимостей"

1. Создайте иерархию классов животных. У каждого класса могут быть уникальные поля, например:
- Cat - уши, лапы, хвост
- Bird - крылья, хвост
2. Создайте методы для отображения информации о животном и звука, который оно издаёт (например, методы Info и Speak). Оба метода могут отображать данные в консоль или в файл, в разных моментах программы (т.е. динамически).
3. Используйте принципы внедрения зависимостей (Dependency Injection) между классами.

## Homework 02

### Тема: "Основы ASP.NET Core"

1. Создайте пустой проект ASP.NET Core.
2. Добавьте необходимые страницы и реализуйте следующие возможности навигации:
- /today – для отображения текущего дня
- /add – форма для добавления цитат на сайт
- /quote – для отображения случайной цитаты из добавленных
- / – начальная страница для навигации между остальным

## Homework 03

### Тема: "Razor Pages"

1. Опишите класс для хранения информации о фильме:
- Название фильма;
- Режиссер;
- Год;
- Краткое описание.
2. Создайте страницу для отображения полной информации.
3. Создайте список фильмов и возможность для его отображения (по названиям).
4. Добавьте навигацию, чтобы при клике на фильм из списка открывалась страница с подробной информацией о нем.

## Homework 04

### Тема: "Представления и модели"

На основе предыдущего задания о фильмах, реализуйте сайт - "кинотеатр":
1. Опишите данные и страницу для отображения информации о фильме:
- доп: отобразить список сеансов
2. Создайте страницу для отображения списка фильмов.
3. На главное странице (Index) отобразите расписание сеансов кинотеатра:
- дата, время, название фильма, цена билета    
Для описания структур данных и хранения списков используйте отдельное пространство и директорию (например, Models), а затем используйте их в Razor страницах.    
На всех страницах используйте общий макет (_Layout), как минимум, для навигации по сайту (главная, список фильмов).

## Homework 05

### Тема: "Паттерн MVC"

1. На основе списка экзаменационных работ выбрать для себя свой проект. Допустимо изменение контекста, напр. темы или правил сайта.
2. Для своего проекта опишите несколько простых страниц и навигацию между ними на основе минимального набора данных.

Например:    
Если бы Вашим проектом был сайт для генерации изображений на основе искусственного интеллекта, в котором предполагается наличие пользователей, нескольких тарифов и взаимодействия с редактором-генератором, то для данного задания вам бы потребовалось описать следующую структуру:
- Controllers
  - MainController.cs (маршрутизация проекта)
- Models
  - Picture.cs (представление данных о картинке)
- Views
  - Main
    - Index.cshtml (главная страница, с описанием проекта)
    - Profile.cshtml (страничка с демо-картинками)

## Homework 06

### Тема: "Куки, авторизация"

Задание. Верификация пользователя.
1. На основе списка экзаменационных работ выбрать для себя свой проект. Допустимо изменение контекста, напр. тематики или правил сайта.
2. Для своего проекта (на основе предыдущего задания) добавьте функционал работы с пользователями и их аутентификацию.

## Homework 07

### Тема: "Авторизация"

Задание. Авторизация пользователя.
1. На основе списка экзаменационных работ выбрать для себя свой проект. Допустимо изменение контекста, напр. тематики или правил сайта.
2. Для своего проекта, разработанного, на основе предыдущих заданий, добавьте пользователям роли и пропишите правила для их авторизации в контроллерах.

## Homework 08

### Тема: "Презентация"

1. На основе списка экзаменационных работ выбрать для себя свой проект. Допустимо изменение контекста, напр. тематики или правил сайта.
2. Для своего готового экзаменационного проекта создать презентацию для защиты. При её создании учитывайте следующие моменты:
- технические возможности для демонстрации (презентации и проекта):
  - есть ли нужное ПО
  - совпадают ли версии
  - будет ли доступ к компонентам
- презентация должна быть в формате pdf
- оформляйте удобочитаемо, учитывайте:
  - цветовую палитру
  - размер шрифта
  - отступы (видимость)
- содержание презентации (минимум):
  - титульный лист
  - описание проекта (сайта)
  - диаграмму переходов (между страницами)
  - диаграмму классов
  - иллюстрацию компонентов и код(!)
  - итоги и перспективы развития
- для лучшего повествования не пишите текст для озвучивания, а составляйте "опорные пункты"

#### Лабораторные работы

## LaboratoryWork 01

### Тема: "Внедрение зависимостей"

Задание. Создайте класс "Человек". Используйте принципы внедрения зависимостей (Dependency Injection) для вывода полной и сокращённой информации.

## LaboratoryWork 02

### Тема: "Razor Pages"

Задание. Создайте сайт, отображающий приветствие и текущую дату.

## LaboratoryWork 03

### Тема: "Представления и модели"

Задание. Создайте сайт, применяя модели страниц, сохраняющий информацию о возрасте человека.

## LaboratoryWork 04

### Тема: "Паттерн MVC"

Задание. Создайте сайт на основе паттерна MVC.

## LaboratoryWork 05

### Тема: "Куки, авторизация"

Задание 1. Реализуйте аутентификацию на сайте по имени пользователя.

Задание 2. Реализуйте аутентификацию на сайте по id пользователя.

## LaboratoryWork 06

### Тема: "Авторизация"

Задание 1. Реализуйте авторизацию на сайте.

Задание 2. Реализуйте авторизацию на сайте для разных ролей.
