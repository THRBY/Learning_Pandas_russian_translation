﻿# Русский перевод книги Майкла Хейдта Learning Pandas
![enter image description here](https://lh3.googleusercontent.com/WXTjTI7htNdgwIk0W-qyR2kO4LLd45BHi5ow0LrnzIWR3KJ2lmtLYRe7CVgceBWCDnyOGACXvjfy)

**О содержании книги**

Глава 1 «Библиотека pandas и анализ данных» – это практическое введение в основные функции библиотеки pandas. Предназначение этой главы – дать некоторое представление об использовании библиотеке pandas в контексте статистики и науки о данных. В этой главе мы рассмотрим несколько принципов, лежащих в основе науки о данных и покажем, как они реализованы в библиотеке pandas. Эта глава задает контекст для каждой последующей главы, связанной с наукой о данных.

[Глава 2 «Запуск библиотеки pandas»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/02_%D0%97%D0%B0%D0%BF%D1%83%D1%81%D0%BA%20%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B8%20pandas.ipynb) проинструктирует читателя по поводу того, как загрузить и установить библиотеку pandas и познакомит его с некоторыми базовыми понятиями библиотеки pandas. Мы также рассмотрим, как можно работать с примерами с помощью iPython и тетрадок Jupiter.

[Глава 3 «Представление одномерных данных с помощью объекта Series»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/03_%D0%9F%D1%80%D0%B5%D0%B4%D1%81%D1%82%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BF%D0%B5%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D0%BE%D0%B9%20%D1%81%20%D0%BF%D0%BE%D0%BC%D0%BE%D1%89%D1%8C%D1%8E%20%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%B0%20Series.ipynb) познакомит читателя со структурой данных Series, которая используется для представления одномерных индексированных данных. Читатель узнает о том, как создавать объекты Series и как работать с данными, хранящимися внутри этих объектах. Кроме того, он узнает об индексах и выравнивании данных, а также о том, как объект Series можно использовать для создание срезов данных.

[Глава 4 «Представление табличных и многомерных данных с помощью объекта DataFrame»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/04_%D0%9F%D1%80%D0%B5%D0%B4%D1%81%D1%82%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%82%D0%B0%D0%B1%D0%BB%D0%B8%D1%87%D0%BD%D1%8B%D1%85%20%D0%B8%20%D0%BC%D0%BD%D0%BE%D0%B3%D0%BE%D0%BC%D0%B5%D1%80%D0%BD%D1%8B%D1%85%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%D1%81%20%D0%BF%D0%BE%D0%BC%D0%BE%D1%89%D1%8C%D1%8E%20%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%B0%20DataFrame.ipynb) познакомит читателя со структурой данных DataFrame, которая используется для представления и индексации многомерных данных. В этой главе читатель научится создавать объекты DataFrame, используя различные наборов статических данных и выполнять отбор определенных столбцов и строк внутри датафрейма. Сложные запросы, операции с данными и индексация будут рассмотрены в следующей главе.

[Глава 5 «Выполнение операций над объектом DataFrame и его содержимым»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/05_%D0%92%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%B9%20%D1%81%20%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%BE%D0%BC%20DataFrame%20%D0%B8%20%D0%B5%D0%B3%D0%BE%20%D1%81%D0%BE%D0%B4%D0%B5%D1%80%D0%B6%D0%B8%D0%BC%D1%8B%D0%BC.ipynb) расширяет предыдущую главу и расскажет о том, как выполнять более сложные операции с объектом DataFrame. Мы начнем с добавления  удаления столбцов и строк, рассмотрим модификацию данных внутри объекта DataFrame (а также создание измененной копии) и выполнение арифметических операций с данными, научимся создавать иерархические индексы, а также вычислять популярные статистики по данным датафрейма.

[Глава 6 «Индексация данных»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/06_%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D1%81%20%D0%B8%D0%BD%D0%B4%D0%B5%D0%BA%D1%81%D0%B0%D0%BC%D0%B8.ipynb) расскажет об использовании различных типов индекса библиотеки pandas (Int64Index, RangeIndex, IntervalIndex, CategoricalIndex, DatetimeIndex, PeriodIndex).

[Глава 7 «Категориальные данные»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/07_%D0%9A%D0%B0%D1%82%D0%B5%D0%B3%D0%BE%D1%80%D0%B8%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D0%B5.ipynb) познакомит читателя с тем, как создавать объекты Categorical  для представления категориальных данных и использовать их в работе.

В [главе 8 «Численные и статистические методы»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/08_%D0%A7%D0%B8%D1%81%D0%BB%D0%B5%D0%BD%D0%BD%D1%8B%D0%B5%20%D0%B8%20%D1%81%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5%20%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B.ipynb) рассматриваются различные арифметические операции над объектами Series  и DataFrame, а также вычисление статистик для объектов pandas.

[Глава 9 «Загрузка данных»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/09_%D0%97%D0%B0%D0%B3%D1%80%D1%83%D0%B7%D0%BA%D0%B0%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85.ipynb) расскажет о том, как можно загрузить данные из внешних источников и записать в объекты Series и DataFrame. Кроме того, в этой главе рассматривается загрузка данных из разных источников, таких как файлы, HTTP-серверы, системы баз данных и веб-службы. Также рассматривается обработка данных в форматах CSV, HTML и JSON.

В [главе 10 «Приведение данных в порядок»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/10_%D0%9F%D1%80%D0%B8%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%D0%B2%20%D0%BF%D0%BE%D1%80%D1%8F%D0%B4%D0%BE%D0%BA.ipynb) будет рассказано о том, как приводить данные в порядок, чтобы они были пригодны для анализа.

[Глава 11 «Объединение, связывание и изменение формы данных»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/11_%D0%9E%D0%B1%D1%8A%D0%B5%D0%B4%D0%B8%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5,%20%D1%81%D0%B2%D1%8F%D0%B7%D1%8B%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%B8%20%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%84%D0%BE%D1%80%D0%BC%D1%8B%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85.ipynb) расскажет читателю о том, как можно взять несколько объектов pandas  и объединить их с помощью операций соединения, слияния и конкатенации.

[Глава 12 «Агрегация данных»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/12_%D0%93%D1%80%D1%83%D0%BF%D0%BF%D0%B8%D1%80%D0%BE%D0%B2%D0%BA%D0%B0%20%D0%B8%20%D0%B0%D0%B3%D1%80%D0%B5%D0%B3%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5.ipynb) расскажет о группировке и агрегации данных. В библиотеки pandas  эти операции выполняются с помощью схемы «разделение – применение – объединение». Читатель научиться использовать эту схему для различных способов группировки данных, а также применять агрегирующие функции для вычисления результатов по каждой группе данных.

[Глава 13 «Анализ временных рядов»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/13_%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B2%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D1%8B%D1%85%20%D1%80%D1%8F%D0%B4%D0%BE%D0%B2.ipynb) расскажет о том, как работать с временными рядами в библиотеке pandas. В этой главе будут освещены широкие возможности библиотеки pandas, существенно облегчающие анализ временных рядов.

[Глава 14 «Визуализация»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/14_%D0%92%D0%B8%D0%B7%D1%83%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F.ipynb) научит вас создавать визуализации данных на основе данных, хранящихся в объектов Series  и DataFrame. Мы начнем с изучения основ, создания простой диаграммы настройки нескольких параметров диаграммы (настройки легенд, меток и цветов). Мы рассмотрим создание нескольких распространенных типов графиков, которые используются для представления различных типов данных.

В [приложении 1 «Советы по оптимизации вычислений в библиотеке pandas»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/%D0%9F%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5%201_%D0%A1%D0%BE%D0%B2%D0%B5%D1%82%D1%8B%20%D0%BF%D0%BE%20%D0%BE%D0%BF%D1%82%D0%B8%D0%BC%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8%20%D0%B2%D1%8B%D1%87%D0%B8%D1%81%D0%BB%D0%B5%D0%BD%D0%B8%D0%B9%20%D0%B2%20%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B5%20pandas.ipynb) даются некоторые рекомендации по ускорению вычислений в pandas.

[Приложение 2 «Улучшение производительности pandas»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/%D0%9F%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5%202_%D0%A3%D0%BB%D1%83%D1%87%D1%88%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BF%D1%80%D0%BE%D0%B8%D0%B7%D0%B2%D0%BE%D0%B4%D0%B8%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20pandas.ipynb) представляет собой перевод одноименного раздела официального пособия по библиотеке pandas  [https://pandas.pydata.org/pandas-docs/stable/ enhancingperf.html](https://pandas.pydata.org/pandas-docs/stable/%20enhancingperf.html).

[Приложение 3 «Используем pandas  для больших данных»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/%D0%9F%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5%203_%D0%98%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D1%83%D0%B5%D0%BC%20pandas%20%D0%B4%D0%BB%D1%8F%20%D0%B1%D0%BE%D0%BB%D1%8C%D1%88%D0%B8%D1%85%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85.ipynb) расскажет, как за счет использования более эффективных типов данных можно уменьшить использование памяти.

В приложениях [4](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/%D0%9F%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5%204_%D0%9F%D1%80%D0%B8%D0%BC%D0%B5%D1%80%20%D0%BF%D1%80%D0%B5%D0%B4%D0%B2%D0%B0%D1%80%D0%B8%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D0%BE%D0%B9%20%D0%BF%D0%BE%D0%B4%D0%B3%D0%BE%D1%82%D0%BE%D0%B2%D0%BA%D0%B8%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%D0%B2%20pandas%20%28%D0%9A%D0%BE%D0%BD%D0%BA%D1%83%D1%80%D1%81%D0%BD%D0%B0%D1%8F%20%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0%20Tinkoff%20Data%20Science%20Challenge%29.ipynb) и [5](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/%D0%9F%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5%205_%D0%9F%D1%80%D0%B8%D0%BC%D0%B5%D1%80%20%D0%BF%D1%80%D0%B5%D0%B4%D0%B2%D0%B0%D1%80%D0%B8%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D0%BE%D0%B9%20%D0%BF%D0%BE%D0%B4%D0%B3%D0%BE%D1%82%D0%BE%D0%B2%D0%BA%D0%B8%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%28%D0%9A%D0%BE%D0%BD%D0%BA%D1%83%D1%80%D1%81%D0%BD%D0%B0%D1%8F%20%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0%20%D0%BF%D1%80%D0%B5%D0%B4%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D0%BD%D0%B8%D1%8F%20%D0%BE%D1%82%D0%BA%D0%BB%D0%B8%D0%BA%D0%B0%20%D0%9E%D0%A2%D0%9F%20%D0%91%D0%B0%D0%BD%D0%BA%D0%B0%29.ipynb) на примере конкурсной задачи Tinkoff  Data  Science  Challenge и конкурсной задачи предсказания отклика ОТП Банка детально показаны этапы предварительной обработки данных, в частности, приведение переменных к нужным типам, обработка редких категорий, импутация пропусков, конструирование признаков, также освещаются специальные процедуры предварительной обработки данных, позволяющие улучшить модель логистической регрессии.

[Приложение 6 «Работа с датами и строками»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/%D0%9F%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5%206_%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D1%81%20%D0%B4%D0%B0%D1%82%D0%B0%D0%BC%D0%B8%20%D0%B8%20%D1%81%D1%82%D1%80%D0%BE%D0%BA%D0%B0%D0%BC%D0%B8.ipynb) посвящено таким задачам, как правильный парсинг дат различного формата, изменение регистра букв в строках, удаление лишних символов из строк, извлечение нужных символов из строк.

[Приложение 7 «Работа с предупреждением SettingWithCopyWarning в библиотеке pandas»](https://github.com/Gewissta/Learning_Pandas_russian_translation/blob/master/Notebooks/%D0%9F%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5%207_%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D1%81%20%D0%BF%D1%80%D0%B5%D0%B4%D1%83%D0%BF%D1%80%D0%B5%D0%B6%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5%D0%BC%20SettingWithCopyWarning%20%D0%B2%20%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B5%20pandas.ipynb) посвящено причинам появления предупреждения SettingWithCopyWarning и способам его устранения.
