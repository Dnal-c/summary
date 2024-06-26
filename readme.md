# Финальный отчет команды "D-nalc"
Контакты сопровождения, в случае возникновения проблем при проверке просьба связаться:

| ФИО              |  Телеграмм  |       Мобильный |
|------------------|:-----------:|----------------:|
| Никоноров Даниил |  @nbv1997   | 8-985-453-96-95 |
| Нуршинов Алимжан |  @alimp_os  |               - |
| Алексеев Алексей | @AlexeevAN  | 8-903-553-72-39 |
| Яблочкин Николай | @yablochk1n |               - |

<div style="height: 20px"></div>

Название команды в заголовке  читать справа-налево. Сделано в надежде защититься от хакерских атак конкурентов 😄

Настоящее название команды представлено на лого

<div id="header" align="center">
  <img src="./logo.svg" alt="">
</div>

## Прототип решения
Ниже перечислим ключевые ссылки:

** Если хотите открывать ссылки в отдельном окне, просьба это делать с помощью функционала в браузере - правый клик - открыть в отдельном окне. Гитхаб не позволил сделать этого из под капота)

1. Прототип решения [Ссылка на прототип](http://87.242.93.110/)
2. Api сервиса поиска видео - [Ссылка на OpenApi search-service](http://178.170.242.192:30042/docs)
3. Api сервиса для закругки видео в индекс - [Ссылка на OpenApi prediction-service](http://178.170.242.192:30043/docs) 

**Просьба**, перед началом работы проверки прототипа ознакомиться с сопровождающей документацией к решению, представленной в пункте **Описание решения**

## Описание решения

В целом, по решению, кажется, что получилось достаточно неплохо или может даже хорошо для MVP по субъективным ощущениям. Сухие факты
- обработали 203 000 записей
- построили валидный поиск, поддерживающий полнотекстовые запросы


Представим ссылки, но хотелось бы, чтобы вы проходили по ним в порядке, описанным в свободном формате после списка. На наш взгляд, так лучше удастся понять логику, и будем вам очень признательны за это 😌

1. Видео "Работа с прототипом" - [UserFlow.mov](https://disk.yandex.ru/i/GVAOza133tIS6Q)
2. Текст к видео "Работа с прототипом" - [UserFlow.pdf](UserFlow.pdf)
3. Презентация -  [Презентация к решению](https://disk.yandex.ru/i/NMr5oKbtYO5DCQ)
4. Документ "Документация к решению" - [Документация к решению](https://www.kaggle.com/code/dnikonorov/summary)
5. Документ "Анализ данных" - [Анализ данных](https://www.kaggle.com/code/dnikonorov/data-analysis)
6. Документ "Процесс сбора данных" - [Процесс сбора данных](https://www.kaggle.com/code/dnikonorov/preprocess-description-with-examples/)
7. Репозиторий с поисковым сервисом - [video-search-service](https://github.com/Dnal-c/video-service)
8. Репозиторий с сервисом сбора данных - [etl-service](https://github.com/Dnal-c/etl-process)
9. Репозиторий с сервисом загрузки файла в индекс [video-prediction-service](https://github.com/Dnal-c/video-prediction-service)
10. Репозиторий с frontend-частью - [frontend-repo](https://github.com/Dnal-c/frontend-repo)

Для того, чтобы понять, как пользоваться прототипом желательно посмотреть видео - [UserFlow.mov](https://disk.yandex.ru/i/GVAOza133tIS6Q), в котором подробно описана работа с прототипом

Так же в файле [UserFlow.pdf](UserFlow.pdf) написана инструкция к видео

После ознакомления с прототипом, предалагаем погрузиться в логику нашего решения и ознакомиться с ней с помощью прочтения [документации к решению](https://www.kaggle.com/code/dnikonorov/summary) 😊

Так же, на всякий случай, представим [ссылку](https://disk.yandex.ru/i/NMr5oKbtYO5DCQ) на презентацию к решению 

Изучив представленное выше, можно сказать, что вы знакомы с нашим решение на уровне medium. Но нам бы хотелось, чтобы вы ушли в глубокие воды 😃

Поэтому ниже представим описание подхода к работе с данными:

[Анализ данных](https://www.kaggle.com/code/dnikonorov/data-analysis) - здесь представлено, какими категориями размышляли, прежде чем сделать итоговый пайп для обработки
[Процесс сбора данных](https://www.kaggle.com/code/dnikonorov/preprocess-description-with-examples/) - здесь представлено, каким образом данные собирались. В файле с анализом так же есть внутрення ссылка на этот файл

Что же, мы перешли на **medium-well**, еще чуть-чуть и можно будет сказать, что знакомы с решением на уровне **well-done**

Ниже представим ссылки на наши репозитории с сервисами

- Репозиторий с поисковым сервисом - [video-search-service](https://github.com/Dnal-c/video-service)
- Репозиторий с сервисом сбора данных - [etl-service](https://github.com/Dnal-c/etl-process)
- Репозиторий с сервисом загрузки файла в индекс [video-prediction-service](https://github.com/Dnal-c/video-prediction-service)
- Репозиторий с frontend-частью - [frontend-repo](https://github.com/Dnal-c/frontend-repo)

Теперь можно сказать, что ознакомление уже **well-done** 

И если вы дошли до этой строчки в рамках проверки, огромное вам спасибо и низкий поклон! 🙏🙏🙏

Так же хотелось бы объяснить, как можно убедиться, что в нашем индексе присутствует видео, которое вы хотели бы видеть в своем поиске:
1. Запросить у нас итоговую выборку. На всякий случай, уточним, что наш датасет собирался из исходного файла, отсортированного по link. Для каждой записи в нашем датасете есть атрибут index, указывающий на индекс в отсортированной исходной выборке.
3. По итоговой выборке пробить поиском по ссылке, есть ли ссылка в выборке. На всякий случай, пример того, как это можно сделать через python:

```python
import pandas as pd
dataset = pd.read_csv('путь_до_нашего_датасета.csv')
display(dataset[dataset['link']=='ВАША ССЫЛКА']['link'])
```

