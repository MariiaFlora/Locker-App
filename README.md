# Locker-App

## Опис проекту
**Locker-App** — це Java-додаток, який демонструє використання механізму блокування для безпечної модифікації чисел у багатопоточному середовищі.

### Основні класи
1. **Main.java** — основний клас програми, який ініціалізує процес обробки чисел та виводить початкові і модифіковані значення чисел.
2. **DataRepository.java** — клас, що надає вихідні дані у вигляді масиву чисел, які потрібно обробити.
3. **DataHandler.java** — клас, що реалізує метод для модифікації чисел із використанням об’єкта блокування для забезпечення потокобезпеки.

### Як працює програма
1. Клас `DataRepository` надає початкові дані у вигляді масиву чисел.
2. Клас `DataHandler` модифікує кожне число, перемножуючи його на три, використовуючи об’єкт блокування для захисту даних у багатопоточному режимі.
3. Основний клас `Main` виконує обробку чисел і виводить результати: початкове значення числа та нове модифіковане значення.

### Вимоги до системи
- Java 8 або вище
- Будь-яке середовище розробки для Java (VSCode, IntelliJ IDEA, Eclipse)
