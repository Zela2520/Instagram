# Instagram
## Содержание
<ul>
  <li>
    <a name="theme">Тема и целевая аудитория</a>
  </li>
  <li>
    <a name="calculation">Расчет нагрузки</a>
  </li>
</ul>
## <a href="#theme">Тема и целевая аудитория</a>
**Instagram** — американская социальная сеть для обмена фотографиями и видео, основанная Кевином Систромом и Майком Кригером.

### О целевой аудитории
Целевой аудиторией являются люди, имеющие отношение к бизнесу, большие компании, общеизвестные деятели и люди, которые хотят делиться своей жизнью в социальных сетях.

- В среднем количество активных пользователей достигает 2-х биллионов;
- Пользователи проводят в среднем 11 часов в месяц в соц. сети;
- 30.8% аудитории - люди от 18 до 24 лет, а  30.3% - люди от 25 до 34 года.

Страны лидеры по размеру аудитории на момент сентября 2023 года:

| Страна      | Пользователей в год, млн. |
| ----------- | ------------------------- |
| Индия       | 230.25                    |
| США         | 159.75                    |
| Бразилия    | 119.45                    |
| Индонезия   | 97.6                      |
| Турция      | 50.7                      |
| Япония      | 48.5                      |
| Мексика     | 45.7                      |

Распределние пользователей за последний месяц (Сентябрь 2023):

| Страна                | Пользователей в месяц, млн. | Пользователей в месяц, %  |
| --------------------- | --------------------------- | ------------------------- |
| CША                   | 435                         | 16.65                     |
| Индия                 | 403.7                       | 10.90                     |
| Бразилия              | 200.2                       | 10.22                     |
| Турция                | 162.4                       | 3.55                      |
| Индонезия             | 161.5                       | 3.50                      |
| Остальные страны      | 1 500                       | 55.18                     |

### Минимально жизнеспособный продукт

1. Создание, редактирование, просмотр профиля;
2. Публикация фото и видео с продолжительностью не более 60 секунд;
3. Возможность поставить лайк и оставить комментарий к посту;
4. Возможность подписаться на пользователя;
5. Возможность просматривать ленту с подписками.

## Расчет нагрузки

### Продуктовые метрики

1. Месячная аудитория: 2 биллиона [[1]](<https://www.statista.com/topics/1882/instagram>);
2. Дневная аудитроия: 500 миллионов [[2]](<https://www.businessdit.com/time-spend-instagram-statistics/>);
3. Среднее время онлайна пользователя - 3 мин. 6 сек [[2]](<https://www.businessdit.com/time-spend-instagram-statistics/>). За это время пользователю удается просмотреть 10 страниц.

#### Регистрация

Перейдем к регистрации: за 2021 год было насчитано 1.28 биллиона пользователей, когда за 2022 1.32 биллиона [[3]](<https://www.statista.com/statistics/183585/instagram-number-of-global-users/>). Это значит, что за год прибавилось 40 000 000 пользователей. Значит, грубой оценкой можно посчитать среднее количество регистраций в день: `4 * 10^7 / 365 = 108 089`. То есть количество регистраций в день достигает 108 тыс.

#### Авторизация

Так как информацию насчет среднего количества входов в аккаунт и регистраций найти не удалось, прибегну к приблизительным расчетам.

Предположим, что седьмая часть пользователей от дневной аудиторий из тех, кто уже зарегестрирован, будет логиниться на сервисе, что будет сопровождаться выдачей сессионного ключа. Итого, количество авторизаций:

> 108 000 + 0.14 x (500 000 000) = 70 млн.

#### Лайки и комментарии

Информация о лайках и комментариях была найдена в источнике [[4]](<https://mention.com/en/blog/instagram-statistics-report/>):

- Среднее количество лайков, оставляемых под постом: 1 261, но всего среднее кол-во лайков в день 2 биллиона;

Суммарное количесво лайков:

> 50 000 000 000 x 1 261 = 63 050 000 млн.

- Среднее количество комментариев, оставляемых под постом: 24.5, но всего среднее кол-во комментариев в день 38 миллиона.

Суммарное количество комментариев:

> 50 000 000 000 x 24.5 = 1 225 000 млн.

#### Лента

Считаем в среднем: имеем число пользователей в день, теперь считаем каджого. Основываясь на статистике о среднем времени (53 минуты), проведенным пользователем на сервисе [[5]](<https://www.businessdit.com/time-spend-instagram-statistics/>), будем предполагать, что большую часть времени он проводит за скроллингом ленты (80%).

Далее нужно понять, сколько времени занимет у пользователя на один пост (просмотр, чтение описания, лайк, комментирование). Мозг может обрабатывать изображение, которое глаз видел только в течение 13 миллисекунд, но человек не сможет сознательно регистрировать эти кадры, поэтому возьмем 2-5 секунды на просмотр фото поста или видео - длина видео (в среднем 10 секунд) и еще 2-5 на проставление лайка и просмотра/написания комментариев. Получаем, что на один пост пользователь будет тратить:

> `Формула`: [время пользователя за скроллиногом ленты] / [время на один пост]\
>
> 0.7 x [(0.8 x 53 x 60) / 10] + 0.3 x [(0.8 x 53 x 60) / 15] = 228 постов в день на пользователя

Стоит учитывать, что посты с фото и видео относятся как 7:3. Посты будут загружаться **каждые 30 постов**. Тогда для одного пользователя всего будет **228 / 30 = 76** загрузок ленты на пользователя в день. Для всех пользователей:

> 76 x 500 000 000 = 38 000 000 000

#### Сводная таблица по среднему количеству действий пользователя по типам в день

| Тип запроса               | Среднее количество действий (в день) |
| ------------------------- | ------------------------------------ |
| Регистрация               | 219    тыс.                          |
| Авторизация               | 70     млн.                          |
| Публикация фото / видео   | 95     млн.                          |
| Проставление лайков       | 2 000  млн.                          |
| Проставление комментариев | 38     млн.                          |
| Просмотр ленты            | 38 000 млн.                          |

### Технические метрики

#### Размер хранения в разбивке по типам данных

- Информация о пользователе

    У пользователя будут следующие поля:

  - `Имя, Фамилия, Никнейм`: все по 32 символа, каждый из которых весит байт;
  - `Почта, Дата рождения`: 4 байта;
  - `Пароль`: в захэшированном виде 32 байта;
  - `Описание`: 64 симовла по байту каждый;
  - `Аватарка`: 50 Кбайт.

  На одного пользователя:

  > 30 + 30 + 30 + 4 x 125 000 + 4 + 4 + 50 000 = 550 098 байт = 4 Мб`

  На всех пользователей понадобится:

  > 2 000 000 000 x 4 = 8 * 10^9 Мб = 8 000 Тб ~= 8 Пб.

- Размер постов

    Начну с размера поста с *фотографией*: средний размер исходной фотографии составляет около 2 Мб. Однако, для хранения на серверах и передачи через сеть, изображение будет сжиматься с использованием алгоритмов оптимизации и сжатия. В результате, средний вес сжатой картинки на платформе составит примерно **300 Кб**.

    Размер *видео* будет зависеть от многих характеристик, но будем брать грубую оценку в среднем. Отталкиваемся от битрейта видео - определяет количество бит, передаваемых в секунду и влияет на качество и размер видеофайла. Обычно на Instagram рекомендуется использовать битрейт от 2 до 5 Mbps [[6]](<https://www.puckermob.com/tech/everything-you-wanted-to-know-about-best-bitrate-for-instagram/>). Для примера возьмем средний битрейт видео в 3 Mbps. Расчет объема данных: для определения размера видеофайла в байтах нужно умножить средний битрейт на длительность видео (в секундах) и поделить на 8 для преобразования из мегабитов в байты.

    > Размер видео (в байтах) = (Средний битрейт x Длительность видео) / 8

    В нашем случае, длительность видео 10 секунд, а средний битрейт 3 Mbps:

    > (3 Mbps x 10 сек) / 8 = 30 Mbps / 8 = 3.75 Мб

    Размер видео (в байтах) = **3.75 Мб**

    Описание к посту займет около 150 байт (возьмем в среднем 150 символов по байту). Итого, пост с картинкой будет весить 300 Кб. В случае с видео - возьмем видео в 10 секунд, которое будет весить 3.75 Мб и пост будет уже весить 3.78 Мб.

    С момента запуска приложения было насчитано около 50 миллиардов фотографий [[7]](<https://earthweb.com/how-many-pictures-are-on-instagram/>), в секунду загружается 1 074 фотографий. Значит, возьмем 3/4 постов с фотографией и 1/4 с видео и посчитаем приблизительный суммарный размер базы, которая будет хранить все посты:

    > 50 000 000 000 x (0.75 x 0.3 + 0.25 x 3.78) = 5 850 000 000 Мб = 58 500 Тб = 58.5 Пб

- Размер лайков

    Для лайков будут учитываться два целочисленных значения по 8 байт каждый - id пользователя, отсавлющий лайк и id поста, на который ставится лайк. При 50 биллионов постов предположим, среднее количество лайков на пост - 1 261. Тогда произведем расчет:

    > 50 000 000 000 x 1 261 x 16 байт = 800 Тб

- Размер комментариев

    В состав комментария будут входить id комментария, id пользователя и поста по 8 байт, содержимое - 1 Кбайт, дата создания 4 байта. Получаем следующее значение:

    > 50 000 000 000 x 24.5 x 1024 = 1 280 Тб

Итого сводная таблица по выделяемому месту для существенных блоков данных:

| Название данных | Количество, шт. | Место, Тб.  |
|-----------------|-----------------|-------------|
| Посты           | 50 000 млн.     | 58 500      |
| Пользователи    | 2 000 млн.      | 8 000       |
| Лайки           | 5 000 блн.      | 800         |
| Комментарии     | 2 500 блн.      | 1 280       |

#### Сетевой трафик

- Взглянем на авторизацию и регистрацию и посчитаем нагрузку:

    > 70 000 000 (в день) x 4 Мб / (24 * 3600) = 12 Гбит/с

    Для пиковой нагрузки умножу показатель в 2 раза:

    > 88 Гбит/с x 2 = 24 Гбит/с

- Рассмотрим загрузку поста. Зная, что за секунду загружается 1 074 постов, посчитаем нагрузку на сеть:

    > 1 074 x (0.75 x 2.2 + 0.25 x 8.2) = 3 973.8 Мб/с = 31 Гбит/с

    Для пиковой нагрузки умножу показатель в 2 раза:

    > 31 Гбит/с x 2 = 62 Гбит/с

- Теперь посчитаем загрузку ленты. Ссылаясь на проделанные расчеты выше, получим:

    > [38 000 000 000 (в день) x 30 (лимит постов для одной загрузки ленты) x (0.7 x 0.3 + 0.3 x 3.78)] / (24 x 3 600) = 1 773 333 Мб/с = 1 773 Гбит/с

    Для пиковой нагрузки умножу показатель в 2 раза:

    > 1 773 Гбит/с x 2 = 3 546 Гб/с

Так как остальные запросы будут не настолько дорогие относительно этих двух, заложу на них 5 Гбит/с.

Получу итоговую сетевую нагрузку:

> 88 + 31 + 1 773 = 1 892 Гбит/с

| Тип данных                | Сетевая нагрузка, Гбит/с | Пиковая сетевая нагрузка, Гбит/с  |
|---------------------------|------------------------|---------------------------------|
| Авторизация & Регистрация | 88                     | 176                             |
| Загрузка поста            | 31                     | 62                              |
| Лента                     | 1 773                  | 3 546                          |

Суточная нагрузка на сеть - `1 892 Гб/с * 3600 * 24 = 163 468 800 Гб/сутки`

### RPS в разбивке по типам запросов

Уже по полученным данным посчитаем кол-во запросов в секунду в среднем:

- Регистрация/Авторизация:   `500 000 000 / (24 * 3600) = 5 787 rps`
- Публикация фото / видео:   `95 000 000 / (24 * 3600) = 1 099 rps`
- Проставление лайков:       `2 000 000 000 / (24 * 3600) = 23 148 rps`
- Добавление комментариев:   `38 000 000 / (24 * 3600) = 439 rps`
- Просмотр ленты:            `38 000 000 000 / (24 * 3600) = 439 814 rps`

Теперь нужно нужно посчитать пиковую нагрузку:

Для авторизации можно умножить среднюю нагрузку на 2, как и с публикацией фото и видео и просмотром ленты. Это объясняется наибольшей активностью пользователей в определенный момент времени.

В случае лайков с комментариями надо умножать среднюю нагрузку на 4. Это обуславливается выкладыванием известной личности какой-либо фотографии - ее начнут активно лайкать и комментировать.

| Тип запроса               | Средняя нагрузка, rps                | Пиковая нагрузка, rps |
| ------------------------- | ------------------------------------ | --------------------- |
| Авторизация               | 5 787                                | 11 574                |
| Публикайия фото / видео   | 1 099                                | 2 198                 |
| Проставление лайков       | 23 148                               | 92 592                |
| Добавление комментариев   | 439                                  | 1756                  |
| Просмотр ленты            | 439 814                              | 879 628               |
| **Итого**                 | **470 287**                          | **987 748**           |
