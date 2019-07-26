# Это путь go разработчика

## Начала

0. Если хочется математики
- https://ru.coursera.org/learn/single-variable-calculus
- https://ru.coursera.org/learn/differentiation-calculus
- https://ru.coursera.org/learn/integration-calculus
- https://ru.coursera.org/learn/applications-calculus
- https://ru.coursera.org/learn/discrete-calculus
- https://www.youtube.com/channel/UC5N5pRddyicAX1QJyJjIIdg

1. Введение. Общая CS теория. Обзор go на практике и первая книга по go
- https://www.ozon.ru/context/detail/id/144946027/
- https://www.codecademy.com/learn/learn-the-command-line
- https://tour.golang.org/
- http://golang-book.ru/

2. Практика и ввередние в алгоритмы
- https://gobyexample.com/
- https://www.ozon.ru/context/detail/id/139296295/
- https://m.habr.com/ru/post/112953/
- https://m.habr.com/ru/post/337260/
- https://m.habr.com/ru/post/146109/
- https://m.habr.com/ru/post/313274/
- https://m.habr.com/ru/post/146901/
- https://m.habr.com/ru/post/431866/
- https://m.habr.com/ru/post/452584/

3. Git - системы управления версиями
- https://try.github.io/
- https://learngitbranching.js.org/
- https://www.codecademy.com/learn/learn-the-command-line

## Середина

4. Продолжение практики. Практику делать в репозитории и на него надо сделать travis CI(билд, тесты, покрытие). Принятие упражнений через пул реквесты.
- https://m.habr.com/ru/company/mailru/blog/314804/
- https://m.habr.com/ru/post/339192/
- https://m.habr.com/ru/post/325468/

- https://github.com/SimonWaldherr/golang-examples
- https://exercism.io/tracks/go
- https://leanpub.com/golang-tdd
- https://quii.gitbook.io/learn-go-with-tests/
- https://gophercises.com/

4.1. Статьи в поддержку практики. Читать с п4 и п5. Подключить travis в телеграмм https://testdriven.io/blog/getting-telegram-notifications-from-travis-ci/## Основы go
- https://www.vld.by/slices-in-go
- https://m.habr.com/ru/company/mailru/blog/314804/
- https://m.habr.com/ru/post/118898/
- https://m.habr.com/ru/post/457728/
- https://m.habr.com/ru/company/otus/blog/453806/
- https://m.habr.com/ru/post/243593/
- https://m.habr.com/ru/post/421411/

### Интерфейсы

- https://m.habr.com/ru/post/276981/
- https://m.habr.com/ru/post/350856/
- https://m.habr.com/ru/post/450386/
- https://m.habr.com/ru/company/funcorp/blog/372199/
- https://m.habr.com/ru/post/332948/

### Стандартная библиотека

- https://m.habr.com/ru/post/307554/
- https://m.habr.com/ru/post/306914/
- https://m.habr.com/ru/post/415171/
- https://medium.com/golangspec/in-depth-introduction-to-bufio-scanner-in-golang-55483bb689b4
- fmt, strings, bytes, math, math/rand, math/big, time, testing, testing/quick, errors, encoding, os, io, io/ioutil, path, sort, net/http, net/url, flags, runtime, context, sync, atomic, crypto, crypto/rand, bufio

### Тестирование

- https://m.habr.com/ru/post/268585/
- https://m.habr.com/ru/company/otus/blog/452772/
- https://m.habr.com/ru/company/badoo/blog/301990/
- https://quii.gitbook.io/learn-go-with-tests/
- https://www.youtube.com/watch?v=ndmB0bj7eyw


### Конкурентность

- https://m.habr.com/ru/company/piter/blog/274569/
- https://m.habr.com/ru/company/ua-hosting/blog/269271/
- https://m.habr.com/ru/post/333654/
- https://m.habr.com/ru/company/ruvds/blog/442648/
- https://m.habr.com/ru/post/308070/
- https://blog.golang.org/share-memory-by-communicating
- https://m.habr.com/ru/post/265833/
- https://m.habr.com/ru/post/271789/
- https://youtu.be/ZMZpH4yT7M0
- https://youtu.be/-K11rY57K7k

### Кодогенерация

- https://m.habr.com/ru/post/269887/



5. Ещё практика
- https://www.hackerrank.com/domains/tutorials/30-days-of-code
- https://www.hackerrank.com/domains/algorithms
- https://www.hackerrank.com/domains/data-structures
- https://www.hackerrank.com/domains/mathematics

6. SQL
- https://www.ozon.ru/context/detail/id/24939188/
- http://www.sql-ex.ru/?Lang=0
- https://www.vividcortex.com/resources/the-ultimate-guide-to-building-database-driven-apps-with-go

7. Конкурентность. Основы
- https://medium.com/@trevor4e/learning-gos-concurrency-through-illustrations-8c4aff603b3

## Завершение

8. Практика конкурентного кода
- https://github.com/mindworker/go-concurrency-exercises

9. Продвинутая теория и практика по конкурентному коду
- https://www.oreilly.com/library/view/concurrency-in-go/9781491941294/
- https://github.com/golang/go/wiki/LearnConcurrency

10. Контейнеры
- https://docs.docker.com/get-started/
- https://kubernetes.io/docs/tutorials/kubernetes-basics/

11. CS 50
- https://youtu.be/SW_UCzFO7X0
- https://javarush.ru/quests/lectures?quest=QUEST_HARVARD_CS50&level=0

*Все упражнения набираем на машине, запускаем и смотрим, что получается.
После освоения третьей части все упражнения и примеры из книг выкладываем в свой репозиторий github.
После освоения https://quii.gitbook.io/learn-go-with-tests/  - пишем на код тесты. Пробуем сначала писать тесты, а потом код.


#### slice

Вот на слайсы упражнения
1. К каждому элементу []int прибавить 1
2. Добавить в конец слайса число 5
3. Добавить в начало слайса число 5
4. Взять последнее число слайса, вернуть его пользователю, а из слайса этот элемент удалить
5. Взять первое число слайса, вернуть его пользователю, а из слайса этот элемент удалить
6. Взять i-е число слайса, вернуть его пользователю, а из слайса этот элемент удалить. Число i передает пользователь в функцию
7. Объединить два слайса и вернуть новый со всеми элементами первого и второго
8. Из первого слайса удалить все числа, которые есть во втором
9. Сдвинуть все элементы слайса на 1 влево. Нулевой становится последним, первый - нулевым, последний - предпоследним.
10. Тоже, но сдвиг на заданное пользователем i
11. Тоже, что 9, но сдвиг вправо
12. Тоже, но сдвиг на i
13. Вернуть пользователю копию переданного слайса
14. В слайсе поменять все четные с ближайшими нечетными индексами. 0 и 1, 2 и 3, 4 и 5...


15. Упорядочить слайс в порядке: прямом, обратном, лексикографическом.

#### map

1. Есть текст, надо посчитать сколько раз каждое слова встречается.
2. Есть очень большой массив(слайс) целых чисел, надо сказать какие числа в нем упоминаются хоть по разу.
3. Есть два больших массива чисел, надо найти, какие числа упоминаются в обоих
4. Сделать Фибоначчи с мемоизацией
5. Пользователь даёт список заказа, программа должна по мапе с наименованиями товаров и ценами, посчитать сумму заказа. И сделать метод добавления новых товаров в мапу, и метод обновления цены уже существующего товара
6. Прочитать статьи про мапы из списка.
7. Сделать 5е, но у нас приходит несколько сотен таких списков заказов и мы хотим запоминать уже посчитанные заказы, чтобы если встречается такой же, то сразу говорить его цену без рассчёта.
8. К 7 добавить, чтобы хранились пользовательские аккаунты со счетом типа "вася: 300р, петя: 30000000р". И перед оформлением заказа, но после его рассчёта мы проверяли, а есть ли деньги у пользователя, и если есть, то списывали сумму заказа.
9. Есть мапа аккаунтов и счетов, как описано в 8. Надо вывести ее в отсортированном виде с сортировкой: по имени в алфавитном порядке, по имени в обратном порядке, по количеству денег по убыванию.
10. Сделать текстовый калькулятор. Пользователь вводит предложения вида "5 плюс 6', а программа выдаёт результат вычисления. Реализовать сложение, вычитание, умножение, деление. Для начала только для двух чисел.
