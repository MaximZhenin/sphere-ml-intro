## Требуется построить 3 рекомендательных системы и вернуть каждый товар с 5 рекомендациями в csv файлах:
* 1) Построить рекомендации, основанные на описании товаров
* 2) Построить рекомендации, основанные на коллаборативной фильтрации
* 3) Построить рекомендации, используя матричную факторизацию

## Входные данные - матрица Interactions.csv - по ссылке https://cloud.mail.ru/public/3DqB/4AGN93myY
* Первый столбец - id юзера
* Второй столбец - id товара
* Третий столбец - тип взаимодействия (PRODUCT - Просмотр, CART - Корзина, PURCHASE - покупка)

## Признаки товаров - sparse матрица item_features_matrix.npz
* Первый столбец - id товара
* Остальные столбцы - фичи непонятного происхождения

# Любые эвристики приветствуются!

## До 23:59 26 ноября необходимо прислать на почту v.zhuravlyov@corp.mail.ru 3 csv файла с темой ДЗ Лекция8 с названиями {Surname}{Name}{NumberOfRecSystem}.csv, где NumberOfRecSystem - номер системы из списка выше, содержащие по 5 рекомендаций для каждого товара в следующем формате:

| Товар1 | Товар2 |  Мера |
| -------| ------ | ------|
| id1    |  id2   |   0.5 |

А также jupyter notebook с кодом, как получили эти рекомендации.
