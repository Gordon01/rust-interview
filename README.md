Вопрос для собеседования Rust-разработчика

# Многопоточность и асинхронность
1. Асинк, особенности реализации в расте, tokio. Как вообще в целом под капотом все работает. [The What and How of Futures and async/await in Rust (с таймкодом) @JonGjengset](https://www.youtube.com/watch?v=9_3krAQtD2k&t=10018s)
2. Многопоточность, трейты Send, Sync. [Crust of Rust: Send, Sync, and their implementors @JonGjengset](https://www.youtube.com/watch?v=yOezcP-XaIw)
3. Синхронизация, Mutex, RwLock. В чем разница, почему у них разные ограничения на типы при одинаковой семантике.

# Остальное
1. Умные указатели: Rc, Arc. Для чего нужны, в чем разница, как работают под капотом. [Crust of Rust: Smart Pointers and Interior Mutability @JonGjengset](https://www.youtube.com/watch?v=8O0Nt9qY_vo)
2. Стек и куча, что куда попадает, зачем нужен Box
3. Алгоритмическая сложность коллекций из стандартной библиотеки. [Документация на std::collections](https://doc.rust-lang.org/std/collections/index.html#performance)
4. От каких гонок защищает раст и как именно это на практике реализовано
5. Лайфтаймы, не лишним будет уметь своими словами обьяснить что именно они показывают. Потому что первый ответ, который приходит в голову (время жизни объекта) - неверен. [Why can't I store a value and a reference to that value in the same struct?](https://stackoverflow.com/questions/32300132/why-cant-i-store-a-value-and-a-reference-to-that-value-in-the-same-struct)
6. В чем разница между параметрическим типом и ассоциированным типом
7. Как работает динамическая диспетчеризация, плюсы-минусы в сравнении с дженериками
