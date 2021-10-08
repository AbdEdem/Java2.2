# Отчёт о тестировании Precision

## Тестирование части JAVA кода

24.09.2021 22:05 - 24.09.2021 22:36 было проведено в приложении IntelliJ IDEA.

На тестирование затрачено: 31 минуты

В результате тестирования выявлены следующие дефекты:
* [Некорректный результат расчёта дополнительных бонусов ](https://github.com/AbdEdem/Java2.2/issues/1#issue-1006762634)


В качестве тестовых данных использовались следующие данные:

* Часть JAVA кода :
```
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```


Тестирование производилось в следующем окружении:
* Laptop, Windows 8 64-bit
* Java v.11.0.12
* IntelliJ IDEA v2021.2.2
