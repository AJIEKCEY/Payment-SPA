# Payment-SPA
SPA платежной страницы(тестовое задание)

    Создать SPA платежной страницы
1.Сверстать макет платежной страницы. В десктопном отображении экран разделяется на 2 колонки: слева форма ввода данных карты (опционально с масками ввода), под формой находится кнопка Оплатить. в правом блоке находится информация о продукте и сумма оплаты. В мобильном представлении блок информации о продукте должен находиться над блоком ввода данных карты. Предусмотреть блок вывода ошибок валидации данных карты

2. Под формой ввода данных карты добавить кнопку Купить в кредит. При нажатии на нее на кнопке Оплатить текст меняется на “Отправить заявку”, форма с картой исчезает, и появляется форма с полями: фамилия, имя, срок кредита в месяцах. При заполнении этой формы сумма в правом блоке должна увеличиться по формуле: изначальная сумма * 1,1 в степени количество месяцев из формы. Допустим изначальная стоимость = 10000, введено в форме 3 месяца, сумма должна измениться с 10000 на 13310.

3. Формы должны отправляться аяксом на файл data.json, в ответ приходит json вида {“success”:true}. После получения ответа клиента перебрасывает либо на страницу успешной оплаты с текстом “Ваша оплата прошла успешно”, либо на страницу с текстом “Мы получили вашу заявку на кредит”

4. Украшать страницы не требуется. В формах достаточно сделать границы 1px border black. Фон белый или серый

5. Логику написать на любом популярном фреймворке (vue, angular, react)

6. Приложение залить на гитхаб

