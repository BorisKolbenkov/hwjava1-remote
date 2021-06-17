# Отчёт о тестировании 
## Краткое описание
16.06.2021 было проведено тестирование Money Transfer

В результате тестирования выявлен дефект:

* [При поплнении счета баланс становится отрицательным, появляется значение -1794967296](https://github.com/BorisKolbenkov/hwjava1-remote/issues/1)    

## Описание процесса тестирования
 В процессе тестирования использовались следующие артефакты:
* [Входные данные в Задаче №1](https://user-images.githubusercontent.com/85697923/122280261-b1c74980-cef1-11eb-9606-10da590622f4.png)


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





