<h2>Чек-листы тестирования веб-приложения TeaSpot</h2>
В рамках тестирования проекта были созданы чек-листы для проверки двух важных модулей. Они охватывают ключевые функциональные возможности разделов, основные пользовательские сценарии и граничные условия, помогая систематизировать проверки и контролировать полноту тестового покрытия.
<br><br>
<details><summary><h3>Чек-лист карточки товара</h3></summary>
<div><h4>Дата: 19.03.2026
  <br>
Окружение: Windows 10 Pro Version 22H2 Google Chrome 145.0.7632.160
<br>
    Результат: Passed — 31 / Failed — 4</h4></div>
<br>
    <table>
    <th>
        Подмодуль
    </th>
    <th>
        Элемент/Функция
    </th>
    <th>
        Проверка
    </th>
    <th>
        Статус
    </th>
    <tr>
        <td align="center" rowspan="6">
            Общий функционал
        </td>
        <td align="center" rowspan="3">
            Контент
        </td>
        <td>
            Отсутствие орфографических ошибок
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Соответствие макету (ссылка)
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Корректность отображения всех элементов
        </td>
        <td>
            <img src="https://img.shields.io/badge/failed%20-%20%23ff0040?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="3">
            Навигация из карточки товара
        </td>
        <td>
            Закрытие карточки товара нажатием кнопки "x"
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Закрытие карточки товара и переход в каталог нажатием кнопки "В каталог"
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Закрытие карточки товара нажатием клавиши ESC
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="11">
            Изображение товара
        </td>
        <td align="center" rowspan="3">
            Галерея изображений
        </td>
        <td>
            Переключение между изображениями нажатием стрелок
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Переключение между изображениями кликами на миниатюры
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Миниатюра активного изображения обведена
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="8">
            Режим просмотра изображений
        </td>
        <td>
            Открытие режима просмотра изображений при клике на изображение
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Переключение между изображениями нажатием стрелок
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Переключение между изображениями нажатием клавиш стрелок
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Увеличение/уменьшение изображения кликом на него
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Увеличение/уменьшение изображения нажатием на кнопку лупы
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Панорамирование увеличенного изображения движением курсора
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Закрытие режима просмотра изображений нажатием кнопки "x"
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Закрытие режима просмотра изображений нажатием клавиши ESC
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="9">
            Покупка
        </td>
        <td align="center" rowspan="4">
            Выпадающий список "Вес"
        </td>
        <td>
            Выбор веса товара из выпадающего списка
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Закрытие выпадающего списка кликом вне области
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            По умолчанию в выпадающем списке выбрано минимальное значение
        </td>
        <td>
            <img src="https://img.shields.io/badge/failed%20-%20%23ff0040?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Изменение цены при изменении веса товара
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="5">
            Добавление товара в корзину
        </td>
        <td>
            Добавление товара в корзину нажатием кнопки "В корзину" и автоматическое
            открытие корзины
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Цена товара в корзине соответствует цене, указанной в карточке товара
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Повторное добавление товара в корзину с тем же весом увеличивает счетчик, а не создает
            дубликат
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Повторное добавление товара в корзину с другим выбранным весом создает новую строку
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            При добавлении товара в корзину, когда в корзине уже находится его максимальное
            количество, отображается сообщение об ограничении
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="9">
            Раздел "Смотрите также"
        </td>
        <td align="center" rowspan="4">
            Навигация
        </td>
        <td>
            Навигация по рекомендованным товарам нажатием стрелок
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Переход к карточке товара по клику на наименование товара
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Переход к карточке товара по клику на изображение товара
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Переход к карточке товара нажатием кнопки "Подробнее"
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="3">
            Выпадающий список "Вес"
        </td>
        <td>
            Выбор веса товара из выпадающего списка
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            По умолчанию в выпадающем списке выбрано минимальное значение
        </td>
        <td>
            <img src="https://img.shields.io/badge/failed%20-%20%23ff0040?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Изменение цены при изменении веса товара
        </td>
        <td>
            <img src="https://img.shields.io/badge/failed%20-%20%23ff0040?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="2">
            Добавление товара в корзину
        </td>
        <td>
            Добавление товара в корзину нажатием кнопки "Заказать" и автоматическое открытие
            корзины
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Цена товара в корзине соответствует цене, указанной в плитке товара
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
</table>
</details>
<details><summary><h3>Чек-лист корзины</h3></summary>
<div><h4>Дата: 20.03.2026
  <br>
Окружение: Windows 10 Pro Version 22H2 Google Chrome 145.0.7632.160
<br>
    Результат: Passed — 79 / Failed — 4</h4></div>
<br>
<table>
    <tr>
        <th>
            Подмодуль
        </th>
        <th>
            Элемент/Функция
        </th>
        <th>
            Проверка
        </th>
        <th>
            Статус
        </th>
    </tr>
    <tr>
        <td align="center" rowspan="10">
            Общий функционал
        </td>
        <td align="center" rowspan="3">
            Контент
        </td>
        <td>
            Отсутствие орфографических ошибок
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Соответствие макету (ссылка)
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Корректность отображения всех элементов интерфейса
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="7">
            Поведение корзины
        </td>
        <td>
            Закрытие корзины нажатием кнопки "x"
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Закрытие корзины кликом за пределами окна корзины
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Закрытие корзины нажатием клавиши ESC
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Переход к карточке товара из корзины при клике на наименование товара
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Сохранение товаров в корзине при переходе на другую страницу сайта
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Сохранение товаров в корзине при обновлении страницы
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Сохранение товаров в корзине после выполнения авторизации
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="15">
            Список товаров
        </td>
        <td align="center" rowspan="9">
            Изменение количества товаров
        </td>
        <td>
            Добавление нескольких наименований товаров
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Изменение количества единиц товара кнопками +/-
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Ввод количества единиц товара с клавиатуры
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            При вводе количества единиц товара, превышающего доступное, отображается ограничение
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность ввода латиницы в поле ввода количества единиц товара
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность ввода кириллицы в поле ввода количества единиц товара
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность ввода спецсимволов в поле ввода количества единиц товара
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность ввода 0 в поле ввода количества единиц товара
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность ввода отрицательных значений в поле ввода количества единиц товара
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="2">
            Рассчет суммы
        </td>
        <td>
            Пересчет стоимости товара при изменении количества единиц товара
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Пересчет итоговой суммы корзины при внесении изменений в состав корзины
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="4">
            Удаление товаров
        </td>
        <td>
            Удаление товара нажатием кнопки "x"
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Удаление товара уменьшением его количества до нуля кнопкой " - "
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Возможность вернуть только что удаленный товар в течение 5 секунд
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Выход из корзины при удалении всех товаров
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="8">
            Блок оформления заказа
        </td>
        <td align="center" rowspan="6">
            Состояние авторизации
        </td>
        <td colspan="2">
            <img src="assets/checklists/nautorized.svg">
        </td>
    </tr>
    <tr>
        <td>
            Переход к форме авторизации и регистрации из блока статуса авторизации
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td colspan="2">
            <img src="assets/checklists/autorized.svg">
        </td>
    </tr>
    <tr>
        <td>
            Переход на страницу Личного кабинета при нажатии на имя пользователя в блоке статуса
            авторизации
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Переход на страницу Личного кабинета при нажатии на e-mail в блоке статуса авторизации
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Выход из аккаунта нажатием на иконку выхода
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="2">
            Кнопка "Оформить заказ"
        </td>
        <td>
            Неактивность кнопки "Оформить заказ" при недоступности доставки в выбранный город
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Кликабельность кнопки "Оформить заказ" при заполненных обязательных полях и
            доступности доставки в выбранный город
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="42">
            Поля ввода данных
        </td>
        <td align="center" rowspan="2">
            Общие проверки
        </td>
        <td>
            Переключение между полями ввода клавишей TAB
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Оформление заказа с существующими именем, email, телефоном и выбранными городом и
            пунктом выдачи
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="5">
            Автозаполнение данных
        </td>
        <td colspan="2">
            <img src="assets/checklists/autorized.svg">
        </td>
    </tr>
    <tr>
        <td>
            Автоматическое заполнение данных в поле "Ваше имя"
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Автоматическое заполнение данных в поле "E-mail для чека"
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Автоматическое заполнение данных в поле "Ваш телефон"
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Возможность редактирования данных в автоматически заполненных полях
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="13">
            Поле "Ваше имя"
        </td>
        <td colspan="2">
            <img src="assets/checklists/positive.svg">
        </td>
    </tr>
    <tr>
        <td>
            Редактирование поля кириллицей и дефисом между буквами
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Редактирование поля латиницей и пробелом между буквами
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Редактирование поля значением, содержащим 2 символа
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Редактирование поля значением, содержащим 3 символа
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Редактирование поля значением, содержащим 99 символов
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Редактирование поля значением, содержащим 100 символов
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td colspan="2">
            <img src="assets/checklists/negative.svg">
        </td>
    </tr>
    <tr>
        <td>
            Невозможность редактирования поля значением, содержащим 1 символ
        </td>
        <td>
            <img src="https://img.shields.io/badge/failed%20-%20%23ff0040?style=for-the-badge">
        </td>
    </tr>
    <tr>
        <td>
            Невозможность редактирования поля значением, содержащим 101 символ
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность редактирования поля спецсимволами
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность редактирования поля цифрами
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность редактирования поля пустым значением
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="10">
            Поле "E-mail для чека"
        </td>
        <td colspan="2">
            <img src="assets/checklists/positive.svg">
        </td>
    </tr>
    <tr>
        <td>
            Редактирование поля существующим e-mail
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td colspan="2">
            <img src="assets/checklists/negative.svg">
        </td>
    </tr>
    <tr>
        <td>
            Невозможность редактирования поля значением без символа @
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность редактирования поля значением без точек в доменной части
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность редактирования поля пустым значением
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность редактирования поля значением, содержащим кириллицу
        </td>
        <td>
            <img src="https://img.shields.io/badge/failed%20-%20%23ff0040?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность редактирования поля значением, содержащим пробелы
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность редактирования поля значением, содержащим спецсимволы (кроме дефиса,
            нижнего подчеркивания и @)
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность редактирования поля значением, содержащим цифры в домене первого уровня
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="12">
            Поле "Телефон"
        </td>
        <td colspan="2">
            <img src="assets/checklists/positive.svg">
        </td>
    </tr>
    <tr>
        <td>
            Редактирование поля существующим номером телефона
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Выбор страны мобильного оператора из выпадающего списка по клику на флаг
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td colspan="2">
            <img src="assets/checklists/negative.svg"><img src="assets/checklists/operator.svg"><img src="assets/checklists/rus.svg">
        </td>
    </tr>
    <tr>
        <td>
            Невозможность ввода латиницы
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность ввода кириллицы
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность ввода спецсимволов
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность ввода пробелов
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность ввода больше 10 символов
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность редактирования поля пустым значением
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность редактирования поля неполным номером телефона (9 символов)
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Невозможность редактирования поля номером телефона с несуществующим кодом оператора
            +7(123)456-78-90
        </td>
        <td>
            <img src="https://img.shields.io/badge/failed%20-%20%23ff0040?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="17">
            Раздел доставки
        </td>
        <td align="center" rowspan="6">
            Поле "Город"
        </td>
        <td>
            Автоматическое определение местоположения и заполнение поля
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Возможность редактирования автоматически заполненного города
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Поиск по городам
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Очистка поля нажатием на "x"
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Появление новых полей ввода при выборе города, куда осуществляется доставка (Омск, Омская
            область)
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Отображение сообщения о невозможности доставки при выборе города, куда доставка не
            осуществляется (г Нарьян-Мар)
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="7">
            Выбор способа доставки по России
        </td>
        <td>
            Переключение между способами доставки
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Изменение способа доставки при выбранном пункте выдачи
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge">
        </td>
    </tr>
    <tr>
        <td>
            Отображение в выпадающем списке пунктов выдачи, соответствующих выбранному городу
        </td>
        <td>
            <img src="https://img.shields.io/badge/failed%20-%20%23ff0040?style=for-the-badge">
        </td>
    </tr>
    <tr>
        <td>
            Выбор пункта выдачи из выпадающего списка
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Поиск пункта выдачи вводом с клавиатуры
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Изменение выбранного пункта выдачи на другой
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            Очистка поля нажатием на "x"
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center" rowspan="3">
            Стоимость доставки
        </td>
        <td>
            При стоимости товаров в корзине меньше 5000 рублей стоимость доставки прибавляется к
            итоговой сумме
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            При стоимости товаров в корзине 5000 рублей (2 товара "Типот Kamjove") доставка
            бесплатная
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td>
            При стоимости товаров в корзине больше 5000 рублей доставка бесплатная
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
    <tr>
        <td align="center">
            Комментарий
        </td>
        <td>
            Поле доступно для ввода
        </td>
        <td>
            <img src="https://img.shields.io/badge/passed%20-%20%2318dc81?style=for-the-badge" />
        </td>
    </tr>
</table>
</details>
