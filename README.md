# Memory Game

## Правила гри
* Потірбно вибрати всі пари однакових зображень
* Якщо пара вгадана вірно - вона залишається відкритою
* Шість рівнів складності 

## Використані матеріали
* Автор ляльок, лялькової постановки та фотограф [Olena Nekora](https://www.facebook.com/people/Olena-Nekora/100050930892384/)

## Нюанси розробки
* Вперше було використано змінні у SCSS типу :root
* Адаптивний дизайн в тому числі під різні розміри екрану і орієнтацію
* Розмітка сторінки grid
* Розмітка HTML формується повністю за рахунок JavaScript шляхом формування DOM
* Динамічне оновлення реалізовано на базі setInterval
* Не все вдалося зробити як хотів - є над чим попрацювати в майбутньому
* Також є один нюанс у роботі гри - не завжди проходить з першої спроби подія click
** можливо  подія не доходить до відповідного класу так як динамічно оновлюється DOM
** можливо за рахунок використання setInterval

## На майбутнє
* Зробити набори різних фото з меньшою розводільною здатністю для різрих рівнів, щоб не перевантажувати мережу
* Зробити індикацію пройдених рівнів 
* Зробити індикацію поточного рахунку спроб вгадування