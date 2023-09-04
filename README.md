# mts_virtual_internship

# Задание 1. Обучить классификатор, используя открытые данные

В экосистеме МТС есть множество продуктов, и у пользователей иногда возникают вопросы по их использованию. Они могут обращаться в службу поддержки (чаты) или пытаться самостоятельно найти ответы, вводя поисковые запросы. При этом алгоритм машинного обучения оперативно подхватывает пользовательские запросы и пытается предложить решение. Если алгоритм верно уловил суть, он дает полезный ответ. То есть с помощью описанного выше алгоритма, мы решаем задачу под названием «классификация интентов».

Задача состоит в том, что бы провести классификацию интентов на основе примеров из предложенного датасета.
Для этого нужно:
1. Обучить классификатор, используя набор фраз из обучающей выборки.
2. Помнить, что классификатор должен уметь самостоятельно оценивать, насколько
фразы из тестовой выборки похожи на примеры из обучающей, и принять решение, к какому классу отнести в итоге эти запросы.

Hints. Для решения задания рекомендуется использовать трансформеры, например BERT, чтобы достигнуть высокого качества работы модели на интентах, которые есть в обучении.


# Задание 2. Доработать модель с учетом новых вводных

Как известно, пользователи не всегда могут формулировать запросы, на которые у модели есть ответы. Чтобы не вызывать их недовольство, работая заведомо некорректно, мы должны отлавливать запросы, относящиеся к тем интентам, которые модель не знает, либо вообще не содержащие в себе интент.

Задача заключается в доработке модели для возможности учета out-of-scope запросов. Для этого нужно:
1. Использовать любые данные и методы. Рекомендуется для начала ознакомиться с теми, которые указаны в полезных материалах во вложении.
2. Предложить варианты, как можно оповещать пользователей о том, что их запрос не относится ни к одному из тех классов, которые модель умеет определять.
