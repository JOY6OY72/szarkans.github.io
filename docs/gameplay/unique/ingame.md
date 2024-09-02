---
description: Команды на Кошкокрафте
icon: material/note-plus
---

# Команды в игре

!!! tip ""
    <> - обязательное значение

    () - необязательное

## **Плейсхолдеры**

**Плейсхолдеры** это текст, который заменяется на другой в чате!

Всё что нужно - ввести плейсхолдер в чат.

| Плейсхолдер | Назначение |
| :---------- | :--------- |
|`[pos]`|Показать в чат своё местоположение|
|`[ping]`|Показать в чат свой пинг|
|`[item]`|Показать в чат предмет в руке. Карты можно будет увидеть, книгу прочитать, а остальное - посмотреть. Не работает в ЛС!|
|`[inv]`|Показать в чат свой инвентарь|
|`[ec]`|Показать в чат свой Эндер-сундук|

## Общение

| Команда | Назначение |
| :------ | :--------- |
|`!<сообщение>` | Отправить сообщение в **глобальный** чат|
|`<сообщение>`|Отправить сообщение в **локальный** чат (40 блоков вокруг тебя)|
|`/msg <ник> <сообщение> /tell <ник> <сообщение> /w <ник> <сообщение>`|Отправить личное сообщение игроку|
|`/mail <send/clear> <ник> <сообщение>`|`send` - отправить котику **оффлайн** сообщение. `clear` - очистит уже имеющиеся сообщения.|

## Действия

| Команда | Назначение |
| :------ | :--------- |
|`/premium`|Перевести свой аккаунт в режим лицензии - позволяет заходить на сервер без пароля. <br><span class="red bold">Если у тебя пиратка - не прописывай! Ты больше не попадёшь на сервер!</span>|
|`/rp`|Загрузить ресурспак сервера|
|`/afk`|Встать в режим AFK. Перед ником появится префикс, и будет уведомление о том, что ты АФК|
|`/afkcheck <ник>`|Проверить в AFK ли котик|
|`/kit (название)`|Без названия - открыть меню китов. С названием - выдать себе кит.|
|`/tpa <ник>`|Отправить запрос на телепортацию к котику. Принять запрос можно только если у тебя есть **Котик+++**|
|`/wspeed <скорость>`|Позволяет установить свою скорость. Число должно быть меньше 1, например `/wspeed 0.5`|
|`/seen <ник>`|Увидеть когда котик был последний раз на сервере|
|`/suicide`|Позволяет покинуть этот мир|
|`/playtime (ник)`|Покажет сколько ты наиграл. Если с ником - покажет сколько наиграл другой котик|
|`/itemframe`|Включить настройку рамки|
|`/art`|Открыть меню рисования на картах|
|`/help`|Получить этот список команд внутри игры|
<!-- |`/menu`|Твоё личное меню котика, в нём есть:<br>- Твоя статистика<br>- Твой баланс<br>- Информация по твоему донатику<br>- Твои персональные настройки<br>- Информация по твоему клану | -->

## Экономика

| Команда | Назначение |
| :------ | :--------- |
|`/balance (ник)`|Проверить твой или чужой баланс АРов|
|`/pay <ник> <сумма>`|Перевести котику АРы с эл. счёта|
|`/cheque <сумма>`|Выписать бумажный чек. Обналичить чек можно нажав `ПКМ` с ним в руке|
|`/baltop`|Топ богачей по АРам|

## РП Команды

| Команда | Назначение |
| :------ | :--------- |
|`/police <wantedlist|warns|list|jaillist>`|Узнать список разыскиваемых, список выговоров, список Офицеров КСБ или список осужденных!|
|`/me <действие>`|Описать действие, совершенное твоим персонажем<br><br>`/me Погладил котика` -> `*Szarkan погладил котика`|
|`/do <описание>`|Описать своего персонажа от 3-го лица<br><br>`/do в зубах сигарета` -> `*В зубах сигарета (Szarkan)`|
|`/roll <число>`|Получить случайное число от 1 до твоего выбранного.<br><br>`/roll 100` -> `*Szarkan рольнул 12 из 100`|
|`/hidenicks`|Скрыть у себя ники котиков|
|`/coinflip`|Подкинуть монетку - выпадет орёл или решка|

## Скины

| Команда | Назначение |
| :------ | :--------- |
|`/skin set <ник>`|Установить себе скин по **нику**|
|`/skin url <ссылка>`|Установить скин по **ссылке**|
|`/skin update`|Обновить свой скин|
|`/skin clear`|Убрать свой скин|
|`/sw <ник/ссылка на скин> <комментарий>`|Добавить скин в меню [быстрой смены скина](../unique/qol.md)|

## **Команды только для** <span class="neon">Котиков+</span>

| Команда | Назначение |
| :------ | :--------- |
|`/sethome (название)`|Поставить точку дома|
|`/spawn`|Телепортироваться на спавн|
|`/home (название)`|Телепортироваться на точку дома. Без названия откроется меню домов|
|`/repair`|Починить предмет в руке|
|`/homes`|Список домов|
|`/heal` `/feed`|Исцелить или накормить себя|
|`/itemname <новое название>`|Поменять название предмета в руке|
|`/hat`|Надеть предмет в руке на голову|
|`/wb`|Открыть виртуальный верстак|
|`/anvil`|Открыть виртуальную наковальню|
|`/loom`|Открыть виртуальный ткацкий станок|
|`/smithingtable`|Открыть виртуальный кузнечный стол|
|`/ec`|Открыть виртуальный эндер-сундук|
|`/back`|Вернуться на место телепортации|
|`/dback`|Вернуться на место смерти|
|`/tpaaccept`|Принять запрос на телепортацию|