# Opencart 3.x only one copy of the product to the cart
The module for Opencart 3.x allows you to add only one copy of the product to the cart.
There are products that make no sense to buy more than 1 copy: digital goods, media products ...
The module does not allow you to add more than 1 piece of the same product to the cart, and thereby saves the user from paying twice for the same thing.


## Только одна копия товара в корзине opencart-3
Модуль позволяет добавить только одну копию товара пользователю в корзину. 
Бывают такие товары, которые нету смысла покупать более 1 копии: цифровые товары, медиапродукция...
Модуль не дает добавить в корзину один и тот же товар более 1 штуки, и тем самым уберегает пользователя заплатить дважды за одно и тоже.


#### Если покупатель пытается добавить более 1 штуки товара в корзину, то добавляется 1 шт. и выводится сообщение:
![screenshot1](https://user-images.githubusercontent.com/106067946/180012035-c1361f15-d781-42f1-be63-d970f994eb04.jpg)


#### Если покупатель у добавленного товара, повторно нажимает на кнопку то количество не увеличивается и выводится сообщение:
![screenshot2](https://user-images.githubusercontent.com/106067946/180024520-c084a0d2-af36-418b-8bf0-b6bcb7d5b951.jpg)


#### Если покупатель пытается обновить количество товара, то не зависимо от введенного количества остается 1 шт. и выводится сообщение:
![screenshot3](https://user-images.githubusercontent.com/106067946/180024765-946b99d5-9057-423a-aba4-3995ccbd5037.jpg)

#### Если у авторизованного покупателя был товар в корзине, затем он был не авторизован и снова добавил этот товар, то при авторизации и сложении одинаковых товаров количество их будет все равно по 1 шт. 
#### Одинаковым товаром считается товар с одинаковым ID, и одинаковым набором опций. Если хоть одна опция отличается, то товар считается разным.

## Установка
* Скачайте install.xml. 
* Запакуйте его в zip архив. 
* Переименуйте архив в only_one_copy_product.ocmod.zip.
* В - Модули / Расширения - Установка расширений  - загрузите архив.
* В - Модификаторы - обновите модификаторы.
