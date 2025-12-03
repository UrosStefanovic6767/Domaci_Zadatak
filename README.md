# Домаћи задатак из Техничке документације
## Задатак
    Програм који на основу унете површине P и висине h израчунава запремину купе V.

### Formula
$$
V = \frac{1}{3} P \cdot h
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
        Console.Write("Унесите дијагоналу квадрата d: ");
        double d = double.Parse(Console.ReadLine());

        double R = d / 2;

        Console.WriteLine("Полупречник описаног круга је: " + R);
    }
}
```

 
### Тест примери
    Тест пример 1 
    Unesi povrsinu P: 10
    Unesi visinu h: 2
    Zapremina kupe je: 6.66666666666667

    Press any key to continue . . .


    Тест пример 2
    Unesi povrsinu P: 15
    Unesi visinu h: 3
    Zapremina kupe je: 15

    Press any key to continue . . .

   ### Објекти
| Naziv promenljive | Tip    | Opis                          |
|-------------------|--------|-------------------------------|
| P                 | double | Površina osnove kupe          |
| h                 | double | Visina kupe                   |
| V                 | double | Izračunava se kao zapremina   |
