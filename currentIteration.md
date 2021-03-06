## Комментарий

[Поведение фильтров](https://drive.google.com/open?id=19ed6m3cI_TUBsXZt3bdyVMl7uOqZhukA)  
Изменилась [страница товара](https://drive.google.com/open?id=1B3ZC-IrNhEYnQMVNtKICLkCcxyN9sHd6)


## Header

![](https://i.imgur.com/t5ha7yv.png)

Тапом по иконке «Поиск» вызывается поисковая строка — кратко говоря, то же поле, что и при выборе города.  
<br/>

![](https://i.imgur.com/mIdMyX5.png)

Расстояние между элементами великовато. Было бы неплохо, если бы оно никогда не превышало 50px.    
<br/>

![](https://i.imgur.com/hIwLmF4.gif)

На мобильных устройствах аниамация шапки не воспроизводится.  
<br/>


## Магазины

![](https://i.imgur.com/X64t9j9.png)

<br/>


## Страница организации

![](https://i.imgur.com/Kn3c0hz.png)

Для ширины вьюпорта менее 420px следует уменшить размер изображения магазина до 152px, ``padding-left`` и ``padding-right`` в блоке описания магазина до 30px и не показывать разделители метаданных, если после них строка прерывается.  
<br/>

![](https://i.imgur.com/PtL90q8.png)

Товары на странице товаров и услуг, результатов поиска, странице магазинов инициализируются таким образом. Если изменить ширину вьюпорта хоть на пиксель и вернуть прежнюю, отображаются корректно.

**В списке товаров и услуг, результатах поиска, на странице магазина, товары следует отображать в одну колонку для брейкпоинта <576px.**



## Моя карта

![](https://i.imgur.com/dGdYHY7.png)

``margin-bottom: 8px`` для ``h2``, ``.text-left`` для строки выбора дат.
Оба элемента следует отображать на одной строке до 480px, пока они не начинают нарушать границы друг друга.

## Поп-ап: выбор города

![](https://i.imgur.com/iHp4THU.png)

Кнопка служит для закрытия поп-апа.
