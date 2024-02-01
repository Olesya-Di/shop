Макет сверстан согласно следующих требований:

1. Сверстать адаптивно. Все должно отображаться красиво, читабельно, понятно для конечного пользователя
2. Верстка должна быть кроссбраузерной
3. Использовать минимум html, больше выносить в css (например, не прописывать класс d-flex в html к каждому flex элементу, а добавлять это свойство через css).
4. Использовать Sass или Scss. И собирать проект через какой-либо сборщик
5. Все элементы на которые можно кликнуть (хотя бы потенциально) должны иметь :hover эффекты на ваше усмотрение.

Логику, которую нужно реализовать:
1. Когда страница только загружается, тарифов (блоки с ценами) не видно. Они появляются плавно один за другим после загрузки страницы.
2. Если нажать на значок $ в любом из тарифов, то значок меняется на ₽ и цены показываются в рублях. Если нажать повторно на ₽, то значок поменяется на евро и цены тоже.
Смена значков и цен должна быть сразу для всех 3х тарифов, а не только для того, где нажали. 
3. Если нажать на слово Month в тарифах, то оно меняется на Day. И цены показываются исходя из расчета: цена за месяц / 30 (округляем до целого). Так же меняется цена/слово сразу на всех тарифах одновременно.
Таким образом можно посмотреть сколько стоит тариф в рублях в день. Или в евро за месяц. И т.п.
