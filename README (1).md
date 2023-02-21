Demo data Yandex Logs API
===========
## Колонки таблицы данных visits
```python
(
    'ym:s:visitID',                     # Идентификатор визита
    'ym:s:watchIDs',                    # Просмотры, которые были в данном визите. Ограничение массива — 500 просмотров
    'ym:s:date',                        # Дата визита
    'ym:s:isNewUser',                   # Первый визит посетителя
    'ym:s:startURL',                    # Страница входа
    'ym:s:endURL',                      # Страница выхода
    'ym:s:pageViews',                   # Глубина просмотра (детально)
    'ym:s:visitDuration',               # Время на сайте (детально)
    'ym:s:bounce',                      # Отказность
    'ym:s:ipAddress',                   # IP адрес
    'ym:s:regionCity',                  # Город (английское название)
    'ym:s:clientID',                    # Идентификатор пользователя на сайте
    'ym:s:networkType',                 # Тип соединения
    'ym:s:goalsID',                     # Идентификатор целей, достигнутых за данный визит
    'ym:s:goalsSerialNumber',           # Порядковые номера достижений цели с конкретным идентификатором
    'ym:s:goalsDateTime',               # Время достижения каждой цели (в часовом поясе UTC+3)
    'ym:s:goalsPrice',                  # Ценность цели
    'ym:s:lastTrafficSource',           # Источник трафика
    'ym:s:lastAdvEngine',               # Рекламная система
    'ym:s:lastReferalSource',           # Переход с сайтов
    'ym:s:lastSearchEngineRoot',        # Поисковая система
    'ym:s:lastSearchEngine',            # Поисковая система (детально)
    'ym:s:lastSocialNetwork',           # Cоциальная сеть
    'ym:s:lastSocialNetworkProfile',    # Группа социальной сети
    'ym:s:referer',                     # Реферер
    'ym:s:lastDirectClickOrder',        # Кампания Яндекс.Директа
    'ym:s:lastDirectBannerGroup',       # Группа объявлений
    'ym:s:lastDirectClickBanner',       # Объявление Яндекс.Директа
    'ym:s:lastDirectClickOrderName',    # Название кампании Яндекс.Директа
    'ym:s:lastClickBannerGroupName',    # Название группы объявлений
    'ym:s:lastDirectClickBannerName',   # Название объявления Яндекс.Директа
    'ym:s:lastDirectPhraseOrCond',      # Условие показа объявления
    'ym:s:lastDirectPlatformType',      # Тип площадки
    'ym:s:lastDirectPlatform',          # Площадка
    'ym:s:lastDirectConditionType',     # Тип условия показа объявления
    'ym:s:from',                        # Метка from
    'ym:s:UTMCampaign',                 # UTM Campaign
    'ym:s:UTMContent',                  # UTM Content
    'ym:s:UTMMedium',                   # UTM Medium
    'ym:s:UTMSource',                   # UTM Source
    'ym:s:UTMTerm',                     # UTM Term
    'ym:s:openstatAd',                  # Openstat Ad
    'ym:s:openstatCampaign',            # Openstat Campaign
    'ym:s:openstatService',             # Openstat Service
    'ym:s:openstatSource',              # Openstat Source
    'ym:s:hasGCLID',                    # Наличие метки GCLID
    'ym:s:lastGCLID',                   # GCLID последнего визита
    'ym:s:firstGCLID',                  # GCLID первого визита
    'ym:s:lastSignificantGCLID',        # GCLID последнего значимого визита
    'ym:s:browserLanguage',             # Язык браузера
    'ym:s:browserCountry',              # Страна браузера
    'ym:s:deviceCategory',              # Тип устройства. Возможные значения: 1 — десктоп, 2 — мобильные телефоны, 3 — планшеты, 4 — TV
    'ym:s:mobilePhone',                 # Производитель устройства
    'ym:s:browser',                     # Браузер
    'ym:s:cookieEnabled',               # Наличие Cookie
    'ym:s:javascriptEnabled',           # Наличие JavaScript
    'ym:s:screenOrientation',           # Ориентация экрана
    'ym:s:screenWidth',                 # Логическая ширина
    'ym:s:screenHeight',                # Логическая высота
    'ym:s:impressionsProductCoupon',    # Промокод ассоциированный с просмотренным товаром
    'ym:s:offlineCallTalkDuration',     # Длительность звонка в секундах
    'ym:s:offlineCallHoldDuration',     # Длительность ожидания звонка в секундах
    'ym:s:offlineCallMissed',           # Пропущен ли звонок
    'ym:s:offlineCallTag',              # Произвольная метка
    'ym:s:offlineCallFirstTimeCaller',  # Первичный ли звонок
    'ym:s:offlineCallURL',              # URL, с которого был звонок (ассоциированная с событием страница)
)
```
Описание полей в [документации](https://yandex.ru/dev/metrika/doc/api2/logs/fields/visits.html)


## Колонки таблицы данных hits
```python
(
    'ym:pv:watchID',                  # Идентификатор просмотра
    'ym:pv:counterID',                # Номер счетчика
    'ym:pv:date',                     # Дата события
    'ym:pv:dateTime',                 # Дата и время события (в часовом поясе счетчика)
    'ym:pv:title',                    # Заголовок страницы
    'ym:pv:URL',                      # Адрес страницы
    'ym:pv:referer',                  # Реферер
    'ym:pv:UTMCampaign',              # UTM Campaign
    'ym:pv:UTMContent',               # UTM Content
    'ym:pv:UTMMedium',                # UTM Medium
    'ym:pv:UTMSource',                # UTM Source
    'ym:pv:UTMTerm',                  # UTM Term
    'ym:pv:hasGCLID',                 # Наличие GCLID
    'ym:pv:GCLID',                    # GCLID
    'ym:pv:isPageView',               # Просмотр страницы. Принимает значение 0, если хит не нужно учитывать как просмотр
    'ym:pv:link',                     # Переход по ссылке
    'ym:pv:download',                 # Загрузка файла
    'ym:pv:notBounce',                # Специальное событие «неотказ» (для точного показателя отказов)
    'ym:pv:lastSocialNetwork',        # Социальная сеть
    'ym:pv:httpError',                # Код ошибки
    'ym:pv:clientID',                 # Идентификатор пользователя на сайте
    'ym:pv:networkType',              # Тип соединения
    'ym:pv:lastSocialNetworkProfile', # Страница социальной сети, с которой был переход
    'ym:pv:goalsID',                  # Идентификаторы достигнутых целей
    'ym:pv:shareService',             # Кнопка «Поделиться», имя сервиса
    'ym:pv:shareURL',                 # Кнопка «Поделиться», URL
    'ym:pv:shareTitle',               # Кнопка «Поделиться», заголовок страницы
    'ym:pv:iFrame',                   # Просмотр из iframe
)
```
Описание полей в [документации](https://yandex.ru/dev/metrika/doc/api2/logs/fields/hits.html)


## Счетчик 1
### Выборка 1
Файл: t1_20220101_20220726_rg_201589066.csv

Цель: 201589066 - ID goals ключевых целей, условия при котором визит или хит можно считать "успешными"

Даты: 2022-01-01 2022-07-26


### Выборка 2
**Данные в выборке 1 не совместимы с данными выборке 2**


Файл visits: t1_20220601_20220621_rg_201589066.csv

Файл hits: t1_20220601_20220621_hits_rg_201589066.csv

Цель: 201589066

Даты: 2022-06-01 2022-06-21


## Счетчик 2
Файл: t2_20190101_20191231_rg_201711160.csv

Цель: 201711160

Даты: 2019-01-01 2019-12-31


## Счетчик 3
Файл: t3_20220101_20230106 rg_184390113,199898941.csv

Цели: [184390113, 199898941] - ID goals ключевых целей, условия при котором визит или хит можно считать "успешными"

Даты: 2022-01-01 2023-01-06


## Счетчик 4
Файл visits: t4_20220601_20220621_rg_106176610.csv

Файл hits: t4_20220601_20220621_hits_rg_106176610.csv

Цель: 106176610

Даты: 2022-06-01 2022-06-21
