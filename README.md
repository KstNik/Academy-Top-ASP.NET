# Academy-Top-ASP.NET

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

#### Лабораторные работы

## LaboratoryWork 01

### Тема: "Внедрение зависимостей"

Задание. Создайте класс "Человек". Используйте принципы внедрения зависимостей (Dependency Injection) для вывода полной и сокращённой информации.
