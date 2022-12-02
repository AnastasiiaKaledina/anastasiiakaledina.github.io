# social-network-react
Приложение социальной сети на React. 

# Как смотреть проект

1. https://anastasiiakaledina.github.io/social-network-react/

Чтобы посмотреть свой профиль в социальной сети, подписаться на пользователей или написать пост, необходимо в нее зайти. Данные для входа:

Логин: nastinapetrova@mail.ru 

Пароль: 123456789

Были использованы как классовые компоненты и их жизненные циклы, так и функциональные с хуками. Проект построен на Redux. Также в проекте использовался API для запросов на сервер.

## Что было реализовано:
— Подгрузка пользователей с сервера, возможность подписаться или отписаться;  
— Логинизация пользователя и подгрузка его данных, а также выход из соц сети;   
— Валидация полей и обработка ошибок неправильного ввода данных;  
— Возможность написать пост или отправить сообщение;  
— При нажатии на пользователя можно провалиться на страницу его профиля;  
— При повторном нажатии на профиль происходит возврат на свою страницу;  
— Можно заменить фото профиля или поменять свой статус двойным щелчком мыши, затем кликнуть на область вне статуса, чтобы статус изменился.  

## Какие были проблемы

— При повторном обновлении страницы после входа данные авторизованного пользователя не приходили и страница не подгружалась (решение: проинициализировать приложение только после положительного ответа об авторизации от сервера)
