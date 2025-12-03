# Домаћи задатак из Техничке документације
## Задатак
    Програм који на основу унете површине P и висине h израчунава запремину купе V.

### Formula
$$
R = \frac{1}{3} d \cdot 2
$$

### Алгоритамска шема
<img width="325" height="883" alt="Treba" src="https://github.com/user-attachments/assets/195def61-d75e-482f-a70d-77b86608b327" />

## Решење 
```csharp
    
   using System;

class Program
{
    static void Main()
    {
        Console.Write("Unesite dijagonalu kvadrata d: ");
        double d = double.Parse(Console.ReadLine());

        double R = d / 2;

        Console.WriteLine("poluprecnik opisanog kruga je: " + R);
    }
}
```

 
### Тест примери
    Тест пример 1 
    Unesite dijagonalu kvadrata d: 5
    poluprecnik opisanog kruga je: 2,5

    C:\Users\urosm\source\repos\ConsoleApp1\ConsoleApp1\bin\Debug\ConsoleApp1.exe (process 18008) exited with code 0 (0x0).
    To automatically close the console when debugging stops, enable Tools->Options->Debugging->Automatically close the console when debugging stops.
    Press any key to close this window . . .



    Тест пример 2
    Unesite dijagonalu kvadrata d: 12
    poluprecnik opisanog kruga je: 6

    C:\Users\urosm\source\repos\ConsoleApp1\ConsoleApp1\bin\Debug\ConsoleApp1.exe (process 4192) exited with code 0 (0x0).
    To automatically close the console when debugging stops, enable Tools->Options->Debugging->Automatically close the console when debugging stops.
    Press any key to close this window . . .


   ### Објекти
| Naziv promenljive | Tip    | Opis                          |
|-------------------|--------|-------------------------------|
| R                 | double | Poluprecnik opisanog kruga    |
| d                 | double | Dijagonala kvadrata           |

