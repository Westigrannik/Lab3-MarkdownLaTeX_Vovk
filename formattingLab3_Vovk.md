## Задание: Комментированнная программа на C#
### Требования к программе:
Имя файла: FormatDemo.cs
Логика:
Запрашивает у пользователя два числа;
Выполняет их сложение;
Выводит результаты в форматированном виде.
Пример реализации:

___
```csharp
Class FormatDemo{
    static void Main(){
        double a = Convert.ToDouble(Console.ReadLine());
        double b = Convert.ToDouble(Console.ReadLine());
        double summ = a + b;
        Console.WriteLine("### Вот результат нашей команды:");
        Console.WriteLine(\$"**Вот он: {summ}**");
    }
}
```
___

Вот вот всё ***СВЕРХУ***