Для того, чтобы ни одно требование не осталось непокрытым я использовала вот такую небольшую матрицу трассируемости. Она не совершенна, но помогла мне.

| Функциональность            | J1  | J-2 | J-3 | J-4 | J-5 | J-6 | J-7 | J-8 | J-9 | J-10 |
| --------------------------- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---- |
| Отображение списĸа ваĸансий | +   | +   | +   | +   | +   | +   | +   | +   | +   | +    |
| Работа фильтров             | -   | +   | +   | +   | +   | +   | +   | -   | -   | -    |
| Поисĸ ваĸансий              | -   | +   | +   | +   | +   | +   | +   | +   | +   | +    |
| Адаптивность                | +   | -   | -   | +   | -   | -   | +   | -   | -   | -    |
| Кнопĸи и ссылĸи             | +   | +   | +   | +   | -   | +   | +   | -   | +   | +    |
| Производительность          | -   | -   | -   | -   | +   | +   | +   | +   | +   | +    |
 В ходе написания тест-кейсов пришлось обратиться к сайту для понимания "ожидаемого результата". В процессе нашлось несколько багов (как, например, возможность выбрать 4 направления в фильтре или невозможность найти вакансию при вводе названия направления собственноручно, не переходя через выпадающие подсказки). Так как задание это в себя не включало, полноценных баг-репортов я не писала (к тому же, требования мне точно неизвестны), но указания на потенциальные баги местами присутствуют в тест-кейсах, которые их выявили. 