### Чек-лист для требований приложения 'Оракул'

#### Общая функциональность

1. Проверить, что приложение реализовано на русском языке и открывается в указанных в требованиях 
браузерах и версиях
2. Проверить, что хостинг приложения осуществляется в соответствии с требованиями
3. Проверить, что в корне проекта находится папка с тестами
4. Проверить, что пользователь получает запрошенные цитаты в всплывающем окне
5. Проверить, что цитаты соответствующей тематики
6. Проверить, что пользователь может подробнее узнать о разработчике
7. Проверить, что пользователь может записать в текстовом поле цитату, нажать на кнопку и она сохранится. 
Сохранение выражается в том, что цитата может быть извлечена в будущем
8. Проверить, что на экране с цитатами имеется счётчик цитат в локальном хранилище 
9. Проверить, что полученные цитаты демонстрируются на экране в виде карточек
10. Проверить, что в оффлайн-режиме приложение демонстрирует уже имеющиеся в локальном хранилище цитаты, а при запросе новой выдаёт понятную ошибку
11. Проверить, что карточку с цитатой можно удалить нажатием на крестик в углу, а также смахиванием налево
(для возможного использования на мобильных устройствах) 
12. Проверить, что цитаты в карточках можно редактировать
13. Проверить, что в приложении есть страница с местонахождением разработчика
14. Проверить, что приложение не загружается в оффлайн-режиме
15. Проверить, что аутентификация и авторизация отсутствуют

#### Проверка качества

1. Проверить, что любое действие внутри приложения выполняется за один клик
2. Проверить, что отклик на любое действие, помимо первого запуска, не превышает 1 секунду
3. Проверить, что скринридеры распознают и проговаривают элементы интерфейса приложения
4. Проверить, что при удалении карточки запрашивается подтверждение

#### Проверка дизайна

1. Проверить, что при первом запуске область для карточек на сторанице пустая
2. Проверить, что на странице "Домой" отображаются поле для ввода, кнопка "Получить цитату"
и кнопка подтвердить и их внешний вид соответствует макету 
[макет](requirements-specification-testing.md#98-макет)
3. Проверить, что на странице "О нас" отображается гугл-карта
4. Проверить, что при разных размерах цитаты размеры карточки подстраиваются под них (достаточно проверить первые 20 цитат) 
5. Проверить, что сверху по центру имеются в наличии две кнопки "Домой" и "О нас" и внешний вид соответствует макету
6. Проверить, что всплывающее окошко с цитатой на странице "Домой" располагается по центру страницы и внешний вид соответствует макету
7. Проверить, что при нажатии на кнопку "О нас" пользователь переходит на соответствующую страницу
8. Проверить, что при нажатии на кнопку "Домой" пользователь переходит на соответствующую страницу


#### Проверка UI/UX

1. Проверить, что приложение со всеми элементами интерфейса адаптивные 
2. Проверить, что внешний вид элементов интерфейса соответствует характеристикам в таблице раздела UI/UX
[таблица](requirements-specification-testing.md#94-ui-и-ux)

#### Данные
1. Проверить, что приложение использует базу данных SQLite 
2. Проверить, что логическая схема данных соответствует реализации в базе данных
[схема](requirements-specification-testing.md#107-логическая-модель-базы-данных)
3. Проверить, что в json запроса и ответа имеется все поля
4. Проверить, что количество символов в поле content не превышает 350 и не меньше 2
5. Проверить, что вставка подобных цитат отклоняется с соответствующим сообщением об ошибке(семантическая проверка нейросетью)
6. Проверить, что нельзя извлечь одну и ту же цитату более 1 раза
7. Проверить, что вписанные в поле и отправленные данные сохраняются в базе данных
8. Проверить, что при удалении карточки с цитатой удаляется соответствующая запись в базе данных. 
9. Проверить, что при редактировании карточки с цитатой обновляется соответствующая запись в базе данных. 

#### Исключения и ошибки
 
1. Проверить, что приложение реализует обработку  ошибок и исключений  
2. Проверить, что есть логирование ошибок и исключений
3. Проверить, что приложение показывает пользователю сообщения об ошибках

#### API

[API](requirements-specification-testing.md#104-api-и-эндпоинты)

1. Проверить, что бекэнд приложение предоставляет API
2. Проверить, что заявленный эндпоинт предоставляют необходимые операции
3. Проверить, что приходящий json соответствует описанию эндпоинта
