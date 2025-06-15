# UI Lab 4
![](terminal-icon.png)
![](gui-icon.png)

Це одна з робіт, які доповнюють основний цикл лабораторних робіт #1-8 (проект **Banking**, [Netbeans](https://netbeans.org/)) з ООП.  Основна мета цих додаткових вправ - познайомитись з різними видами інтерфейсів користувача та засобами їх створення. Згадувані 'базові' роботи розміщено в [окремому репозиторії](https://github.com/liketaurus/OOP-JAVA) (якщо будете робити завдання на "4" або "5" раджу переглянути [діаграму класів](https://github.com/liketaurus/OOP-JAVA/blob/master/MyBank.png), аби розуміти які методи є у класів).

В ході роботи вам пропонується виконати **наступне завдання** - [Робота 4: GUI з Matisse](https://github.com/ppc-ntu-khpi/GUI-Lab2-Starter/blob/master/Lab%204%20-%20Matisse/Lab%204.md)
  
**Додаткове завдання** (для тих хто зробив все і прагне більшого): [дивіться тут](https://github.com/ppc-ntu-khpi/GUI-Lab2-Starter/blob/master/Lab%204%20-%20Matisse/Lab%20-%204%20-%20add.md)

Всі необхідні бібліотеки містяться у теці [jars](https://github.com/ppc-ntu-khpi/GUI-Lab2-Starter/tree/master/jars). В тому числі - всі необхідні відкомпільовані класи з робіт 1-8 - файл [MyBank.jar](https://github.com/ppc-ntu-khpi/GUI-Lab2-Starter/blob/master/jars/MyBank.jar). Файл даних лежить у теці [data](https://github.com/ppc-ntu-khpi/GUI-Lab2-Starter/tree/master/data).

---
## На "трійку" 
1. Завантажте jar-файл з усіма потрібними классами (*Bank, Customer, Account* та ін.) з наших попередніх лаб - [MyBank](https://github.com/ppc-ntu-khpi/GUI-Lab2-Starter/blob/master/jars/MyBank.jar) 
2. Створіть в Netbeans новий проект з назвою MatisseDemo (або використайте проект, створений в ході виконання попередньої роботи). *УВАГА! Чекбокс *Create Main Class* треба **очистити** (**не створювати виконуваний клас**)!* 
3. Додайте до проекту завантажену вами бібліотеку - правою кнопкой на проекті, обрати *Properties*, потім у дереві категорій обрати *Libraries* (другий пункт зверху), натиснути у правій частині вікна кнопку *Add JAR/Folder*, обрати jar-файл, завантажений у п. 1, натиснути *Ok* 
4. Додайте до проекту нову форму JFrame. З допомогою Matisse створіть інтерфейс, [прототип](https://github.com/ppc-ntu-khpi/GUI-Lab2-Starter/blob/master/Lab%204%20-%20Matisse/GUI-Lab-4.PNG) якого ви бачили на початку цього завдання. *УВАГА! Форма має або масштабуватись у зручний спосіб, або зміну її розмірів слід заборонити (властивість **Resizeable**)!*
5. Вивчіть автоматично згенерований код у файлі, впевніться, що ви розумієте як він має працювати 
6. Запустіть проект у звичайний спосіб. Ви маєте побачити вікно, ідентичне до прототипу. Продемонстрируйте результат викладачеві. 

![](https://github.com/ppc-ntu-khpi/34-matisse-DESTROYchambo/blob/defbdb04468f35b5881dae87e8de8b9c35e772e7/images/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-06-12%20185250.png)

## На "чотири"
<b>
  
2. Напишіть обробники подій для елементів керування, завдяки яким би при виборі клієнта та натисненні кнопки **Show** виводилась інформація про нього та всі його рахунки
  
3. Кнопка **About** має демонструвати діалогове вікно з інформацією про програму та її розробників (**[JOptionPane](https://docs.oracle.com/javase/7/docs/api/javax/swing/JOptionPane.html)**)

</b>

![](https://github.com/ppc-ntu-khpi/34-matisse-DESTROYchambo/blob/3145f2e956dcd794deb51c996af56f22b10101d4/images/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-06-15%20135531.png)

## На "п'ять"
1. Кнопка **Report** має виводити у нижній частині вікна звіт за клієнтами такого ж виду, як у роботі номер 8 (див. CustomerReport).
2. Запустіть проект, впевніться, що все працює як очікувалось. Продемонстрируйте результат викладачеві. 

![](https://github.com/ppc-ntu-khpi/34-matisse-DESTROYchambo/blob/0a8a2e34ba56b061d0ff9d53938c265354c3b223/images/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-06-15%20135820.png)

![](https://img.shields.io/badge/Made%20with-JAVA-red.svg)
![](https://img.shields.io/badge/Made%20with-%20Netbeans-brightgreen.svg)
![](https://img.shields.io/badge/Made%20at-PPC%20NTU%20%22KhPI%22-blue.svg) 
