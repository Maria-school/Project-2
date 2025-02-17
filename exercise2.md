# Список тестовых сценариев.
Для сайта https://www.saucedemo.com/.

## Сценарий №1. Проверка успешного прохождения авторизации(стандартный пользователь):
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
***
## Сценарий №2. Проверка успешного прохождения авторизации(блокированный пользователь):
1. Перейти на страницу авторизации
2. В поле "Username" ввести "locked_out_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
***
## Сценарий №3. Проверка успешного прохождения авторизации(проблемный пользователь):
1. Перейти на страницу авторизации
2. В поле "Username" ввести "problem_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
***
## Сценарий №4. Проверка успешного прохождения авторизации (сбой пользователь):
1. Перейти на страницу авторизации
2. В поле "Username" ввести "performance_glitch_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
***
## Сценарий №5. Проверка открытия меню сайта:
1. Перейти на страницу авторизации 
2. Авторизоваться (успешно)
3. Нажать на три черточки в левом верхнем углу страницы
***
## Сценарий №6. Проверка закрытия меню сайта:
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать на три черточки в левом верхнем углу страницы
4. Нажать на крестик в правом верхнем углу появившегося меню
***
## Сценарий №7. Проверка пункта "All Items" меню сайта:
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать на любой товар в открывшемся окне
4. Нажать на три черточки в левом верхнем углу страницы
5. Нажать на слова "All Items"
***
## Сценарий №8. Проверка пункта "About" меню сайта:
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать на три черточки в левом верхнем углу страницы
4. Нажать на слова "About"
5. нажать стрелочку "Назад"
***
## Сценарий №9. Проверка пункта "Logout" меню сайта:
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать на три черточки в левом верхнем углу страницы
4. Нажать на слова "Logout"
***
## Сценарий №10. Проверка пункта "Reset App State" меню сайта:
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать на три черточки в левом верхнем углу страницы
4. Нажать на слова "Reset App State"
***
## Сценарий №11. Проверка открытия карточки товара:
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать на изображение товара(1 способ) или нажать на наименование товара(2 способ)
***
## Сценарий №12. Проверка возврата к списку товаров из карточки товара:
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать на изображение товара(1 способ) или нажать на наименование товара(2 способ)
4. Нажать на слова "Back to products" под тремя черточками меню 
***
## Сценарий №13. Проверка открытия корзины товаров:
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать изображение тележки в правом верхнем угулу страницы сайта
***
## Сценарий №14. Проверка открытия "продолжение шоппинга" после перехода в корзину товаров:
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать изображение тележки в правом верхнем угулу страницы сайта
4. Нажать на прямоугольник слева "Continue shopping"
***
## Сценарий №15. Проверка добавления товара в корзину:
- способ 1
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать на изображение товара(1 способ) или нажать на наименование товара(2 способ)
4. Нажать на слова "Add to cart" под описанием товара в карточке товара
- способ 2
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать на слова "Add to cart" рядом с наименованием товара на главной странице сайта
***
## Сценарий №16. Проверка удаления товара из корзины:
- способ 1
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать на изображение товара(1 способ) или нажать на наименование товара(2 способ)
4. Нажать на слова "Add to cart" под описанием товара в карточке товара
5. Нажать на слова "Remove" рядом с описанием товара в карточке товара
- способ 2
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать на слова "Add to cart" рядом с наименованием товара на главной странице сайта
4. Нажать на слова "Remove" рядом с наименованием товара на главной странице сайта
- способ 3
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Добавить товар в корзину нажатием на слова "Add to cart"
3. Нажать изображение тележки в правом верхнем угулу страницы сайта
4. Нажать на слова "Remove" рядом с наименованием товара
***
## Сценарий №17. Проверка сортировки товаров по Name (A to Z) и(Z to A):
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать на значок воронки под изображением тележки
4. Выбрать из выпадающего списка Name (A to Z) или Name (Z to A)
***
## Сценарий №18. Проверка сортировки товаров по Price (low to high ) и (high to low):
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать на значок воронки под изображением тележки
4. Выбрать из выпадающего списка  Price (low to high ) или (high to low)
***
## Сценарий №19. Проверка оформления заказа товара:
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Добавить товар в корзину "Add to cart" под описанием товара или из карточки товара
4. Нажать изображение тележки в правом верхнем угулу страницы сайта
5. Нажать зеленую кнопку "Checkout"
6. В окне "Checkout: Your Information" заполнить поля "First name", "Last name","Zip/Postal Code"
7. Нажать зеленую кнопку "Continue"
8. В открывшемся окне "Checkout: Overview" нажать зеленую кнопку "Finish"
9. В открывшемся окне "Checkout: Complete!"нажать зеленую кнопку "Back home"
***
## Сценарий №20. Проверка возврата в корзину , если пользователь передумал оформлять заказ товара:
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Добавить товар в корзину "Add to cart" под описанием товара или из карточки товара
4. Нажать изображение тележки в правом верхнем угулу страницы сайта
5. Нажать зеленую кнопку "Checkout"
6. В окне "Checkout: Your Information" нажать на белый прямоугольник "Cancel"
***
## Сценарий №21. Проверка перехода в социальную сеть Твиттер:
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать на зеленый кружок с изображением птички Твиттер в левом нижнем угулу сайта
***
## Сценарий №22. Проверка перехода в социальную сеть Фейсбук:
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать на зеленый кружок с изображением буквы "F" в левом нижнем угулу сайта
***
## Сценарий №23. Проверка перехода в социальную сеть linkedin:
1. Перейти на страницу авторизации
2. Авторизоваться (успешно)
3. Нажать на зеленый кружок с изображением букв "in"  в левом нижнем угулу сайта