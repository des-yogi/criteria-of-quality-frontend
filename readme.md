# Критерии хорошей верстки

Обязательные и необязательные критерии оценки вёрстки.


## 1. Разметка


### 1.1. Разметка проходит валидацию на [validator.w3.org/nu](https://validator.w3.org/nu/)

Проверяются все сверстанные страницы.


### 1.2. Отсутствуют грубые ошибки

Примеры грубых ошибок: ссылки не являются ссылками, `<br><br>` вместо параграфов.

Примеры негрубых (условно-допустимых) ошибок: `<div>` вместо `<section>`, `<header>` или `<article>`, отсутствие списка в одноуровневой навигации.


### 1.3. Разметка работоспособна без стилей и скриптов

Страница без стилей и скриптов, будучи открыта в браузере, выглядит логично и работает:

- видна чёткая иерархия блоков (заголовки),
- не видны элементы, ненужные или не работающие без стилей и скриптов (пример: бургер главного меню),
- интерактивные элементы (ссылки, в т.ч. якорные, формы) видны и работоспособны.

**Исключение:** страницы, работоспособность которых невозможна без стилей/скриптов.


### 1.4. Использована методология БЭМ, отсутствуют типовые ошибки

CSS-классы, использованные в разметке, написаны по БЭМ ([Описание методологии](https://ru.bem.info/methodology/quick-start/)). Предпочтительным является использование [диалекта Two Dashes](https://ru.bem.info/methodology/naming-convention/#Стиль-two-dashes) (`__` как разделитель для элемента и `--` как разделитель для модификатора).

Типовые ошибки:

- повторение разделителя более одного раза в одном классе: `block__element__element` или `block--modifier--modifier`,
- модификатор как единственный класс DOM-узла: `<div class="block--modifier">`.


## 2. Стилизация

TODO: нет транслита


## 3. Дополнительные файлы




## 4. Оптимизация

### 4.1. Использованы доступные семантические возможности

TODO: label и прочее про формы, типографика?


## 5. Автоматизация




## 6. Адаптивность




## 7. Разное
