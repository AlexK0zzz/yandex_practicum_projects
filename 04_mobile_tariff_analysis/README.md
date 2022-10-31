# mobile_tariff_analysis

## Определение перспективного тарифа для телеком-компании

Чтобы скорректировать рекламный бюджет, коммерческому департаменту компании "Мегалайн" необходимо понять, какой тариф приносит больше денег. Необходимо провести предварительный анализ тарифов на небольшой выборке клиентов. На основании данных о клиентах (регион, тариф, количесвтво звонков и сообщений) за 2018 год необходимо проанализировать поведение клиентов и сделать вывод — какой тариф лучше.

**Цель исследования:**

 1. определить поведение клиентов оператора (уровни потребления минут разговора, сообщений, объёма интернет-трафика);
 2. проверить гипотезы:
  1. средняя выручка пользователей тарифов "Ультра" и "Смарт" различаются;
  2. средняя выручка пользователей из Москвы отличается от выручки пользователей из других регионов.
 
**Ход исследования**

Входные данные - информация о пятистах пользователях: регион, тариф, сколько звонков, сообщений и интернет-трафика использовали за 2018 год. Информации о качестве данных нет, поэтому перед основным исследованием будет проведён обзор данных, а также их предобработка.

**Результат**

Поведение пользователей каждого тарифа:
 - пользователи тарифа "Смарт" в среднем расходуют бОльшую часть предоставленных минут разговора (418 из 500) и сообщений (33 из 50), а интернета в среднем им требуется почти на 1 ГБ больше (15.8 ГБ), чем входит в тариф (15 ГБ); средняя выручка составляет 1290р.;
 - пользователи тарифа "Ультра" расходуют всего около 20% минут (527 из 3000) и 5% сообщений (49 из 1000); в среднем у них остаются неизрасходнованными около 11 ГБ интернет-трафика; средняя выручка 2070р.
 
Результаты проверки гипотез:

 1. Средняя выручка пользователей тарифов "Ультра" и "Смарт" различается. Первая гипотеза подтвердилась.
 2. Средняя выручка пользователей из Москвы и средняя выручка пользователей из других регионов оказалась равна. Таким образом, вторая гипотеза была не подствердилась.
 
Таким образом, независимо от региона тариф "Ультра" оказался прибыльнее тарифа "Смарт", что мы могли увидеть как по распределениям, так и путём проверки гипотез.