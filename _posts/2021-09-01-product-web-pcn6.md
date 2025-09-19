---
layout: post
title: Веб-интерфейс к пожарно-охранной системе PCN6 фирмы RITM
tags: [ПРОЕКТ]
---

Альтернативный веб-интерфейс к системе мониторинга стационарных объектов PCN6 производства фирмы RITM для охранного предприятия.

![_config.yml]({{ site.baseurl }}/images/pcn_screen/1.png)

- Легкий и быстрый веб-интерфейс (в сравнении со стандартным веб-интерфейсом)
- Разграничение объектов по операторам (групповой доступ)
- Разграничение обрабатываемых тревог по операторам (возможно выделить отдельно пожарные/охранные тревоги)
- Двойная авторизация: по SSL-сертификату и по логину/паролю
- Частичное управление пользователями через административный интерфейс
- Оператор — только просмотр
- AJAX-обновление
- Информирование о недоступности **InetServer**
 
<!--more-->


### Технологии
Для проекта использовал следующие технологии:
- PHP (Yii2 Framework)
- Bootstrap
- MySQL
- SSL (аутентификация)
- Python (pytest + selenium) - тесты

### Всплывающие подсказки 
При наведении на объект/тревогу

![_config.yml]({{ site.baseurl }}/images/pcn_screen/2.png)

[Нажмите сюда для увеличения]({{ site.baseurl }}/images/pcn_screen/2.png)


### Описание объекта

![_config.yml]({{ site.baseurl }}/images/pcn_screen/3.png)

[Нажмите сюда для увеличения]({{ site.baseurl }}/images/pcn_screen/3.png)


### Журнал объекта

![_config.yml]({{ site.baseurl }}/images/pcn_screen/4.png)

[Нажмите сюда для увеличения]({{ site.baseurl }}/images/pcn_screen/4.png)


### Пользователи

![_config.yml]({{ site.baseurl }}/images/pcn_screen/5.png)

[Нажмите сюда для увеличения]({{ site.baseurl }}/images/pcn_screen/5.png)


### Группы объектов

![_config.yml]({{ site.baseurl }}/images/pcn_screen/6.png)

[Нажмите сюда для увеличения]({{ site.baseurl }}/images/pcn_screen/6.png)


### Обработка тревоги
Обработка одновременно несколькими операторами, видны действия по тревоге. 

![_config.yml]({{ site.baseurl }}/images/pcn_screen/7.png)

[Нажмите сюда для увеличения]({{ site.baseurl }}/images/pcn_screen/7.png)


### Завершение обработки

![_config.yml]({{ site.baseurl }}/images/pcn_screen/8.png)

[Нажмите сюда для увеличения]({{ site.baseurl }}/images/pcn_screen/8.png)
