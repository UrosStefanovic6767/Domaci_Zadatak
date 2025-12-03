# Домаћи задатак из Техничке документације
## Задатак
    Програм који на основу унете дужине дијагонале квадрата d израчунава полупречник 
    описаног круга R. 

### Formula
$$
R = \frac{d}{2} 
$$

### Алгоритамска шема
<img width="237" height="400" alt="Snimak ekrana 2025-12-03 153537" src="https://github.com/user-attachments/assets/e9aa8daa-167e-46ba-ba30-d47f24297da6" />

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

