Модуль "Новая почта"
============================

Автор
------------
ZinitSolutions GmbH http://zinitsolutions.de/

Версия: 1.0.0

Поддерживаемые языки
-----------------------
Русский

Требования
-------------------
PHP > 5.4
<br/>
OpenCart 1.5.6.x.

Описание
---------------
Модуль дает возможность выбора отделение Новой почты в заданном городе и высчитывает стоимость доставки при оформлении заказа, используя API Новой почты версии 2.0.

Установка
---------------
### 1. Установите модуль

Прежде всего, скачайте [дистрибутив](https://github.com/), распакуйте его, и скопируйте файлы из каталога `upload` в корень opencart-магазина (Не забудьте создать резервную копию ваших данных).

Для корректной работы выберите русскую версию Opencart-магазина, а также нужную страну и регион. Для этого нужно зайти в **Система** > **Настройки**, выбрать нужный магазин и нажать **Изменить**. На вкладке **Локализация** выберите страну, регион и измените параметры **Язык** и **Язык администратора** на **Rassian**, после этого сохраните изменения.

### 2. Включите модуль в настройках

Модуль настраивается в админке по адресу: *Дополнения > Модули доставки > Новая почта*.

*API-ключ* — необходимо получить в [личном кабинете](https://my.novaposhta.ua/settings/index#apikeys) my.novaposhta.ua.

*Город отправителя* — город, с которого будут отправляться заказы.

*Адрес отправителя* — адрес, с которого будут отправляться заказы.

*Статус* — включения/выключения модуля.

*Обновить список городов и отделений в БД* — обновление списка городов и отделений, находящихся в **Адрес отправителя**.

### 3. Пользуйтесь модулем!

После оформления заказа в админ-панели появится информация о данном заказе, при редактировании которого в разделе **Новая почта** есть возможность указать отправителя и получателя. Чтобы попасть на страницу редактирования заказа нужно перейти в **Продажи** > **Заказы** и нажать **Изменить**.

После нажатия на клавишу **Оформить** на сайте Новой почты должна появиться накладная с информацией о данном заказе.

Лицензия
-----------------
[Лицензия](doc/licence.txt)

История изменений
-----------------

* 1.0.0
 * Первый релиз