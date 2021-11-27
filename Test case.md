# Тест кейс № 1
## Название (Title)
Воспроизведение тестовой ситуации банковского перевода с заданными параметрами
## Шаги (Steps to reproduce):
1. В редакторе IntelliJ IDEA создать новый класс Main (Main.java) с указанным ниже кодом (в т.ч. переменными):
``` Java
public class Main {
}
```
2. Ввести метод public static void main(String[] args) {
```Java
public class Main {
    public static void main(String[] args) {

    }
}
```
3. Объявить следующие переменные:

- имя "CurrentBalance", значение "2_000_000_000" - обозначает текущий баланс счёта клиента;
- имя "Payment", значение "500_000_000" - обозначает сумму перевода;
- имя "NewBalance", значение "CurrentBalance + Payment" - обозначает итоговое значение нового баланса по счету клиента после перевода.

```Java
public class Main {
    public static void main(String[] args) {
        int CurrentBalance = 2_000_000_000;
        int Payment = 500_000_000;
        int NewBalance = CurrentBalance + Payment;
        }
}
```
4. Ввести оператор System.out.println со значением "NewBalance"
```Java
public class Main {
    public static void main(String[] args) {
        int CurrentBalance = 2_000_000_000;
        int Payment = 500_000_000;
        int NewBalance = CurrentBalance + Payment;
        System.out.println(NewBalance);
    }
}
```
## ## Ожидаемый результат
По результатам расчетов запущенной программой выдается результат "2500000000"