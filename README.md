# Рекомендация тарифов телеком компании
В вашем распоряжении данные о поведении клиентов. 

## Задача

Построить модель для задачи классификации, которая выберет подходящий тариф с значением *Accuracy* не меньше 0.75. 

**Описание данных**

- `сalls` — количество звонков,
- `minutes` — суммарная длительность звонков в минутах,
- `messages` — количество sms-сообщений,
- `mb_used` — израсходованный интернет-трафик в Мб,
- `is_ultra` — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).

## Используемые библиотеки

- pandas
- sklearn
  
## Итоги проекта

На тестовой выборке модель случайного леса  показала Accuracy = 0.7791.
