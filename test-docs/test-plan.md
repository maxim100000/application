### Введение

#### Основная информация

Документ описывает методы и подходы к тестированию, которые будут использоваться
тестировщиком для тестирования фронтенда и бекенда приложения.

Объект тестирования — работоспособность функций приложения в десктопных браузерах и в
операционной системе Android.

#### Цель документа

Определить существующую информацию о проекте и программных компонентах, подлежащих тестированию.
- Описать стратегии тестирования, которые будут использоваться.
- Определить необходимые ресурсы для проведения работ по тестированию.
- Привести результаты тестирования.

Все найденные ошибки будут фиксироваться в баг-репортах.

### Рамки проекта

#### Область тестирования фронтенда

В объем работ по тестированию приложения входит:

- Соответствие дизайна макету
- Техническая возможность занесения и получения цитат
- Техническая возможность редактирования цитат


#### Область тестирования бекенда

В объем работ по тестированию приложения входит:

- Реализация добавления и удаления цитат из базы данных
- Реализация извлечения цитат из базы данных и изменения

### План работы

Стороны договорились следовать следующему плану работы:

1. Подготовка плана тестирования.
2. Согласование тест-плана.
3. Функциональное тестирование и отчеты об ошибках.

### План и стратегия тестирования

#### Функциональное тестирование

Цель функционального тестирования состоит в том, чтобы убедиться, что весь
программный продукт работает в соответствии с требованиями, и в приложении не
появляется существенных ошибок. Функциональное тестирование является наиболее
существенной частью тестирования программного обеспечения, включающее в себя
проверку различных аспектов системы. Программный продукт должен пройти все
запланированные тесты. Только в этом случае можно быть уверенным в его качестве.

#### Цель: 
Обеспечение надлежащего качества функциональности

#### Техника:

- Выполнить каждый сценарий, используя допустимые и недопустимые данные.
- Ожидаемые результаты возникают при использовании достоверных данных.
- Соответствующие сообщения об ошибках или предупреждения
отображаются, когда используются неверные данные.
- Каждый пункт проверен.
- Подготовлено тестовое окружение, приложение готово к тестированию
на тестовой площадке.

#### Критерий приемки:
- Все дымовые тесты пройдены.
- Нет блокирующих багов.
- Все баги с высоким приоритетов поправлены.
- Тесты пройдены.

### Процедура тестирования

#### Основные виды тестирования

- модульное
- интеграционное
- системное
- дымовое
- критического пути
- функциональное
- интерфейсов
- удобства использования
- доступности
- интернационализации
- API
- совместимости
- операционное

В рамках тест-пдана не будут выполняться тестирование:

- безопасности
- А/В 
- альфа, бета, гамма
- производительности
- отказоустойчивости
- надежности
- приёмочное
- регресионное
- повторное
- инсталляционное

### Сообщения об ошибках

Отчеты об ошибках создаются для того, чтобы предоставить разработчику и руководителю 
проекта исчерпывающую информацию об обнаруженных ошибках. Они должны быть полезны 
при определении причин ошибок и их исправлении.

Уровень серьёзности и приоритетность:

- Тривиальный -дефекты, которые не влияют на работу приложения (приоритетность низкая)
- Незначительный - дефекты, которые пользователь не замечает, так как они не влияют на функциональность (приоритетность низкая)
- Серьёзный - дефекты, которые заметны пользователю, но не мешают работать приложению (приоритетность средняя)
- Критический - ограничена работа важной части приложенияы, но пользоваться им обходными путями можно (приоритетность средняя)
- Блокирующий - приложение не работает (приоритетность высокая)

Информация, указанная в каждом отчете об ошибке:

- Идентификатор
- Название программного продукта.
- Серьёзность дефекта и приоритет
- Окружение: браузер, версия Android, разрешения экрана и др. параметры воспроизведения
- Краткое описание, представляющее собой краткое описание проблемы
- Частота возникновения дефекта
- Шаги для воспроизведения
- Ожидаемый результат
- Фактический результат
- Статус: открыт, в работе, исправлен, закрыт
- Дополнительная информация
- Автор
- Исполнитель
  
### Ресурсы

#### Список браузеров

| Браузеры | Версия    |
|----------|-----------|
| Yandex   | последняя |
| Firefox  | последняя |

#### Список устройств

| Устройства | Версия |
|------------|--------|
| Android    | 7      |
| Android    | 13     |

### Критерии качества

Продукт должен работать в соответствии с требованиями и не должен содержать 
критических и блокирующих дефектов в окончательной версии

### Риски процесса тестирования

- Незапланированные изменения и модификации приложения
- Незапланированные изменения в требованиях к приложению
- Задержки в обнаружении и исправлении ошибок.

### Обязанности тестировщика

Процесс контроля качества, регистрация обнаруженных ошибок в отчётах об ошибках

### Результаты тестирования

Итоговый отчет, описывающий проведенные тесты, их результаты и выводы по качеству программного обеспечения

