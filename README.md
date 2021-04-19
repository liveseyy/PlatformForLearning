<h1>Онлайн-платформа для обучения</h1>

Приложение написано при помощи Django3 и с визуальной частью на Bootsrap4

Пример структуры курса:
  Предмет/Тема
  --Курс (1)
  ----Модуль (1)
  ------Контент (1) (текст/видео/фото/файл)
  ------Контент (2) (текст/видео/фото/файл)
  ----Модуль (2)
  ------Контент (1) (текст/видео/фото/файл)
  ------Контент (2) (текст/видео/фото/файл)
      ...

Доступна регистрация и аутентификация.

Заниматься созданием курсов могут лишь пользователями с правами на создание, изменение и удаление курсов.
Создание курсов происходит на специальной странице (CMS).

Пользователи могут записываться на курс и просматривать его содержимое.

Модули курсов и предметы кэшируются посредством Memcached.
