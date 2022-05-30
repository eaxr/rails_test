# rails_test

для теста, собрано по книжке "Ruby on Rails Tutorial: Learn Web Development With Rails". Сначала на одной версии ruby и RoR, потом изменение на другую.

Сборка приложения и создание пользователя:
![alt text](https://github.com/eaxr/rails_test/blob/main/images/rails_1.gif?raw=true)

Заполнение базы данных postgresql тестовыми пользователями через команду:
```rails db:seed```
![alt text](https://github.com/eaxr/rails_test/blob/main/images/rails_2.gif?raw=true)

Создание пользователя, активация и следование за другими пользователями, но найден жук! Если создать пост, то он не отображается в feed, а только то, что написали другие польжователи:
![alt text](https://github.com/eaxr/rails_test/blob/main/images/rails_3.gif?raw=true)

Отоборажается только в профиле, а не в ленте:
![alt text](https://github.com/eaxr/rails_test/blob/main/images/rails_4.gif?raw=true)

Починил модель и сообщения появились в ленте:
![alt text](https://github.com/eaxr/rails_test/blob/main/images/rails_5.gif?raw=true)

Найден новый жук, если логиниться с запоминание, то выход из аккаунта не срабатывает:
![alt text](https://github.com/eaxr/rails_test/blob/main/images/rails_6.gif?raw=true)

Изменен механизм очищения сессии, после этого выход из аккаунта заработал:
![alt text](https://github.com/eaxr/rails_test/blob/main/images/rails_7.gif?raw=true)
