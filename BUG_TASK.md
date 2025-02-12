# Задание
## Перечислить все имеющиеся баги на предоставленном скриншоте, указать их приоритет
<img src="https://github.com/Kaledo1337/myavito/blob/main/images/avito.jpg" title="avitoQA" alt="avitoQA" style ="max-width: 100%"/>

---

# Найденные баги 

---

## 1. 

<img src="https://github.com/Kaledo1337/myavito/blob/main/images/bug1_breadcrumbs.png" title="bug" alt="bug" style ="max-width: 100%"/>

### Путь навигации отображён некорректно. "Хлебные крошки" должны правильно отображать путь на странице, он должен соответствовать структуре сайта. На скриншоте же приведён не полный вариант навигации.
### Правильно :Главная > Хобби и отдых > Велосипеды > Горные
### Приоритет Low

---

## 2.
<img src="https://github.com/Kaledo1337/myavito/images/blob/main/bug2_location.png" title="bug" alt="bug" style ="max-width: 100%"/>

### Объявления на странице отображаются некорректно. Был выбран метод отображения объявлений с указанием их геолокации в указанном городе , но на веб - сайте объявления представлены в виде сетки (4 ряда по 3 элемента в каждом), что, вероятнее всего, не соответствует требованиям. 
### Приоритет Low

--- 

## 3.
 <div>
    <img src="https://github.com/Kaledo1337/myavito/images/blob/main/bug3_avito.png" title="bug" alt="bug" style ="max-width: 100%"/>&nbsp
    <img src="https://github.com/Kaledo1337/myavito/images/blob/main/bug3_avito1.png" title="bug" alt="bug" style ="max-width: 100%"/>&nbsp
</div>

### По сравнению с уже реализованной функциональностью на сайте https://www.avito.ru/ (скриншот слева), в предоставленной версии страницы веб - сайта отсутствует фильтрация анкет по радиусу поиска (скриншот справа).
### Приоритет Low

---

## 4.
 <div>
    <img src="https://github.com/Kaledo1337/myavito/images/blob/main/bug4_avito.png" title="bug" alt="bug" style ="max-width: 100%"/>&nbsp
    <img src="https://github.com/Kaledo1337/myavito/images/blob/main/bug4_avito1.png" title="bug" alt="bug" style ="max-width: 100%"/>&nbsp
</div>

### По сравнению с уже реализованной функциональностью на сайте https://www.avito.ru/ (скриншот слева), в предоставленной версии страницы веб - сайта отсутствует фильтрация анкет по акциям (скриншот справа).
### Приоритет Low

---

## 5.
 <div>
    <img src="https://github.com/Kaledo1337/myavito/images/blob/main/bug5_avito.png" title="bug" alt="bug" style ="max-width: 100%"/>&nbsp
    <img src="https://github.com/Kaledo1337/myavito/images/blob/main/bug5_avito1.png" title="bug" alt="bug" style ="max-width: 100%"/>&nbsp
</div>

### По сравнению с уже реализованной функциональностью на сайте https://www.avito.ru/ (скриншот слева), в предоставленной версии страницы веб - сайта отсутствует фильтрация анкет по типу рамы велосипеда (скриншот справа).
### Приоритет Low

---

## 6.
<img src="https://github.com/Kaledo1337/myavito/images/blob/main/bug6_showbutton.png" title="bug" alt="bug" style ="max-width: 100%"/>

### В левом нижнем углу на синей кнопке написано "Показать 9 объявлений", в то время как указанное количество найденных объявлений по поиску не соответствует данному значению (61).
### Приоритет Low

---

## 7.
<img src="https://github.com/Kaledo1337/myavito/images/blob/main/bug7_error.png" title="bug" alt="bug" style ="max-width: 100%"/>

### В верхней правой части страницы присутствует форма, которая указывает о наличии ошибок на веб - сайте. Не ясен контекст данной ошибки, непонятно, из - за чего она выводится.
### Приоритет Low

---

## 8.
<img src="https://github.com/Kaledo1337/myavito/images/blob/main/bug8_pagination.png" title="bug" alt="bug" style ="max-width: 100%"/>

### В результате поиска было найдено 61 совпадение по фильтрам, на 1 странице помещается 12 объявлений, всего потребуется 6 страниц, чтобы отобразить все необходимые объекты на данный момент. При попытке пользователя перейти на 7 страницу и далее, он увидит 404 ошибку.
### Приоритет Medium

---

## 9.
<img src="https://github.com/Kaledo1337/myavito/images/blob/main/bug9_time.png" title="bug" alt="bug" style ="max-width: 100%"/>

### При отображении товаров в правом нижнем объявлении неправильно определилась ближайшая станция метро продавца. 
### Приоритет Medium

---

## 10.
<img src="https://github.com/Kaledo1337/myavito/images/blob/main/bug10_notMoscow.png" title="bug" alt="bug" style ="max-width: 100%"/>

### На веб - сайте осуществляется фильтрация, в результате которой сначала должны выводится московские объявления, но на скриншоте объявление с г.Липецк отобразилось раньше московских. Данный баг имеет средний приоритет из - за того, что фильтрами в общем не запрещено выводить объявления из других городов. 
### Приоритет Medium

---

## 11.
<img src="https://github.com/Kaledo1337/myavito/images/blob/main/bug11_brand.png" title="bug" alt="bug" style ="max-width: 100%"/>

### На странице был выставлен фильтр по бренду велосипеда Author, но в выведенных объявлениях отобразился велосипед другого бренда (Atom).
### Приоритет Medium

---

## 12.
<img src="https://github.com/Kaledo1337/myavito/images/blob/main/bug12_wrong_station.png" title="bug" alt="bug" style ="max-width: 100%"/>

### Станция метро "Звенигородская" находится в Санкт - Петербурге, в то время как на веб - сайте осуществляется фильтрация, в результате которой сначала должны выводится московские объявления. Данный баг имеет средний приоритет из - за того, что фильтрами в общем не запрещено выводить объявления из других городов. 
### Приоритет Medium

---

## 13.
<img src="https://github.com/Kaledo1337/myavito/images/blob/main/bug13_wrong_station_name.png" title="bug" alt="bug" style ="max-width: 100%"/>

### Неправильно указано название станции метро "Ховрино" Московского метрополитена. Если потенциальный покупатель, который живёт ближе к данной станции, захочет отфильтровать объявления по своей станции метро, то он не увидит объявления из - за ошибки в названии станции и ,как следствие, не сможет приобрести нужный ему товар. 
### Приоритет High

---

## 14.
<img src="https://github.com/Kaledo1337/myavito/images/blob/main/bug14_descending_prices.png" title="bug" alt="bug" style ="max-width: 100%"/>

### На странице был выставлен фильтр по убыванию цены, но самым первым товаром в списке идёт велосипед с не самой большой ценой из предоставленных объявлений. Если такая же ошибка присутствует в фильтрах по возрастанию цены (от меньшей к большей) то слишком высокая цена первых объявлений может отпугнуть потенциального покупателя.
### Приоритет High
