# Отчёт о тестировании 
## Краткое описание
16.06.2021 было проведено тестирование Money Transfer

В результате тестирования выявлен дефект:

* [При поплнении счета баланс становится отрицательным, появляется значение -1794967296](https://github.com/BorisKolbenkov/hwjava1-remote/issues/1)    

## Описание процесса тестирования
 В процессе тестирования использовались следующие артефакты:
* [Входные данные в Задаче №1](https://github.com/netology-code/javaqa-homeworks/tree/master/programming#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-1---money-transfer)


## Шаги к воспроизведению

  * Запустить программу IntelliJ IDEA
  * В Project нажать Alt+Insert и выбрать Java Class
  * В поле окна New Java Class ввести Main
  * Скопировать код из тестовых данных
  * В поле окна New Java Class ввести Main
  * Ввести код программы
  * Нажать Ctrl+Shift+F10
  * Ожидаемый результат: значение 2500000000

## Тестирование производилось в следующем окружении:

* Windows 10 x64
* Java 11
* Git Bash 
* IntelliJ IDEA 

## В качестве тестовых данных использовался код программы: 
```

public class main {
    public static void main(String[] args)
    {int account = 2_000_000_000;
        int add = 500_000_000;
        int total = account + add;
        System.out.println(total);





