# Проекты по анализу данных
В данном репозитории хранится портфолию проектов, сделанных мною во время учёбы в Яндекс.Практикуме на курсе по анализу данных.

Проекты в основном представлены в виде файлов, подготовленных в Jupyter Notebook на языке Python.

<table>
 <thead valign="top">
    <tr>
       <td>№</td>
       <td>Название проекта</td>
       <td>Описание</td> 
       <td>Использованные инструменты и библиотеки</td> 
   </tr> 
</thead>
<tbody  valign="top">
    <tr>
       <td>1</td>
       <td>
          <b>
             <a href="https://github.com/galaleksey/yandex-praktikum/tree/main/01_preprocessing_credit-scoring">
             Исследование надежности заемщиков</a>
         </b>
     </td>
     <td>
        Определил, какие факторы и каким образом влияют на способность клиента банка погасить кредит в срок.
    </td>
    <td>
        <code>pandas</code><br/>
        <code>pymystem3</code> (для лемматизации)<br/>
        <code>nltk.stem</code> (для стемминга)<br/>
        <code>numpy</code>
    </td>
</tr>
<tr>
   <td>2</td>  
   <td>
      <b>
         <a href="https://github.com/galaleksey/yandex-praktikum/tree/main/02_eda_apartment-advertisements">
         Исследование объявлений о продаже квартир</a>
     </b>
 </td>
 <td>
    Изучил влияние различных факторов на стоимость недвижимости.
</td>
<td>
    <code>pandas</code><br>
    <code>matplotlib.pyplot</code><br>
    <code>numpy</code><br>
    <code>datetime</code><br>
</td>
</tr>
<tr>
   <td>3</td>
   <td>
      <b>
         <a href="https://github.com/galaleksey/yandex-praktikum/tree/main/03_statistics_telecom">
         Определение перспективного тарифа для телеком компании</a>
     </b>
 </td>
 <td>
    Исследовал поведение клиентов телеком оператора при пользовании тарифами. Определил, какой тариф лучше.
</td>
<td>
    <code>
        <code>pandas</code><br>
        <code>matplotlib.pyplot</code><br>
        <code>stats.scipy</code><br>
        <code>numpy</code><br><br>
    </code>
</td>
</tr>
<tr>
   <td>4</td>
   <td>
      <b>
         <a href="https://github.com/galaleksey/yandex-praktikum/tree/main/04_games-market-research">
         Исследование рынка компьютерных игр</a>
     </b>
 </td>
 <td>
    Провел исследовательский анализ данных о продажах игр, составил портрет пользователей из каждого региона, 
    спрогнозировал приоритетные направления для продаж на следующий год.
</td>
<td>
        <code>pandas</code><br>
        <code>matplotlib.pyplot</code><br>
        <code>stats from scipy</code><br>
        <code>numpy</code>
</td>
</tr>
<tr>
   <td>5</td>
   <td>
      <b>
         <a href="https://github.com/galaleksey/yandex-praktikum/tree/main/05_etl_flights">
         Аналитика в авиакомпании</a>
     </b>
 </td>
 <td>
    Загрузил данные из различных источников (БД, парсинг сайта) и проанализировал их.
</td>
<td>
        <code>pandas</code><br>
        <code>matplotlib.pyplot</code><br>
        <code>requests</code><br>
        <code>BeautifulSoup</code><br>
        Другие инструменты: <code>SQL</code>.
</td>
</tr>
<tr>
   <td>6</td>
   <td>
      <b>
         <a href="https://github.com/galaleksey/yandex-praktikum/tree/main/06_business_metrics">
         Аналитика в Яндекс.Афише</a>
     </b>
 </td>
 <td>
    Провел исследование и рассчитал метрики: DAU, WAU, MAU, sticky factor, Retention Rate, LTV, SAS, ROMI.<br>
    Выяснил как люди пользуются продуктом, когда они начинают покупать, сколько денег приносит каждый клиент, 
    когда клиент окупается. 
</td>
<td>
    <code>
        pandas,<br>
        matplotlib.pyplot,<br>
        seaborn,<br>
        numpy.<br><br>
        Визуализации: boxplot, histogram, line plot, heatmap, group bar, stacked bar.
    </code>
</td>
</tr>
<tr>
   <td>7</td>
   <td>
      <b>
         <a href="https://github.com/galaleksey/yandex-praktikum/tree/main/07_a-b-testing_e-commerce">
         Принятие решений в бизнесе на основе данных</a>
     </b>
 </td>
 <td>
    Приоритизировал гипотезы, проанализировал данные, полученные за время проведения А/В теста: кумулятивная 
    выручка, средний чек и конверсия по группам. 
    Проанализировал статистическую значимость с помощью критерия Манна-Уитни: конверсии, различий в среднем чеке 
    между группами, сырыми и очищенными данными.
</td>
<td>
    <code>
        pandas,<br>
        matplotlib.pyplot,<br>
        matplotlib.lines,<br>
        numpy,<br>
        datetime,<br>
        scipy.stats.
    </code>
</td>
</tr>
<tr>
   <td>8</td>
   <td>
      <b>
         <a href="https://github.com/galaleksey/yandex-praktikum/tree/main/08_vizualization_restaurants">
         Анализ рынка заведений общественного питания Москвы</a>
     </b>
 </td>
 <td>
    Провел исследовательский анализ данных о заведениях общественного питания Москвы.<br>
    Cделал общий вывод и дал рекомендации о виде заведения, количестве посадочных мест, а также районе 
    расположения для открытия небольшого кафе.
</td>
<td>
    <code>
        pandas,<br>
        plotly.express,<br>
        re.<br>
    </code>
</td>
</tr>
<tr>
   <td>9</td>
   <td>
      <b>
         <a href="https://github.com/galaleksey/yandex-praktikum/tree/main/09_conversion_funnel_a-b">
         Анализ воронки продаж интернет-сервиса по продаже продуктов питания</a>
     </b>
 </td>
 <td>
    Изучил воронку конверсии, проанализировал все шаги, которые покупатель проходит до покупки, выявил вероятные 
    проблемы. Исследовал результаты проведенного А/А/В-теста.
</td>
<td>
    <code>
        pandas,<br>
        plotly.express,<br>
        numpy,<br>
        math,<br>
        proportions_ztest from statsmodels.stats.proportion.
    </code>
</td>
</tr>
<tr>
   <td>10</td>
   <td>
      <b>
         Анализ взаимодействия пользователей с карточками Яндекс.Дзен
     </b>
 </td>
 <td>
    Создал дашборд для менеджеров по анализу контента популярной блог-платформы.<br>
    Сагрегировал данные и сверстал <a href="https://public.tableau.com/profile/galaleksey#!/vizhome/Project11_Zen/Dashboard">дашборд в Tableu.Public</a> с основными типами графиков и элементами управления.
</td>
<td>
    <code>
        pandas,<br>
        sqlalchemy.create_engine
    </code>
</td>
</tr>
<tr>
   <td>11</td>
   <td>
      <b>
         <a href="">
         Применение машинного обучения в прогнозировании оттока клиентов фитнес-центра</a>
     </b>
 </td>
 <td>
    Провел исследовательский анализ данных о клиентах, проанализировал корреляцию признаков.<br>
    Построил модель прогнозирования оттока клиентов.
</td>
<td>
    <code>
        pandas,<br>
        matplotlib.pyplot,<br>
        seaborn,<br><br>
        train_test_split from sklearn.model_selection,<br>
        StandardScaler from sklearn.preprocessing,<br>
        LogisticRegression from sklearn.linear_model,<br>
        RandomForestClassifier from sklearn.ensemble,<br>
        accuracy_score, precision_score, recall_score, f1_score, roc_auc_score from sklearn.metrics,<br>
        RandomizedSearchCV from sklearn.model_selection,<br>
        dendrogram, linkage from scipy.cluster.hierarchy,<br>
        KMeans from sklearn.cluster.
    </code>
</td>
</tr>
<tr>
   <td>12</td>
   <td>
      <b>
         <a href="https://github.com/galaleksey/yandex-praktikum/tree/main/12_final_project">
         Выпускной проект</a>
     </b>
 </td>
 <td>
   TBD
</td>
<td>
   TBD
</td>
</tr>
</tbody>
</table>
