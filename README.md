# SPORTS-BETTING

Разработка веб приложение с адаптацией под мобильный вид "Ставки на спорт". Реализовано 2 страницы:
1.	[Домашняя страница]: 
    * На странице отображаются текущие и предстоящие события;
  	* Вид отображения событий - список;
    * При клике на событие - осуществляется переход на индивидуальную страницу [Детали события].
2. Страница [Детали события]: 
    * Названия команд;
    * Дата события;
    * Отображение текущего коэффициента (вариативный) в виде радиокнопки/переключателя с единственным вариантом выбора: ['на победу хозяев', 'на ничью', 'на победу гостей'];
    *	Кнопка "Сделать ставку": 
        + Элемент активен только после выбора коэффициента;
        + После клика осуществляется переход на [Домашняя страница];
        + В верхней части [Домашняя страница], перед списком событий, выводится уведомление "Спасибо, ваша ставка [МАТЧ ТАКОЙ-ТО, СТАВКА ТАКАЯ-ТО] принята";
        + Уведомление отображается единоразово.

### Приложение можно посмотреть перейдя по ссылке https://test-sports-betting.netlify.app/
