## Создание дашборда для Superstore

Создала дашборд в Exel на основе данных файла Sample - Superstore.xls. 

![Sample - Superstore Dashboard.jpg](https://github.com/LenaMitrofanova/DE-101/blob/main/module1/Sample%20-%20Superstore%20Dashboard.jpg)

+ Использовала функцию Vlookup для добавления данных о региональных менеджерах  (Person) и возвратах (Returns)  в основную таблицу:

        =ВПР(M2; People!$A:$B; 2; 0)
        =ЕСЛИОШИБКА(ВПР(B2; Returns!$A:$B; 2; 0); "No")
+ Для построения спарклайна и расчета ключевой метрики *Profit ratio* добавила в сводную таблицу вычисляемое поле.
+ В качестве срезов выбрала следующие параметры: Годы, Категории, Регионы.
![Ключевые метрики и срезы.jpg](https://github.com/LenaMitrofanova/DE-101/blob/main/module1/%D0%9A%D0%BB%D1%8E%D1%87%D0%B5%D0%B2%D1%8B%D0%B5%20%D0%BC%D0%B5%D1%82%D1%80%D0%B8%D0%BA%D0%B8%20%D0%B8%20%D1%81%D1%80%D0%B5%D0%B7%D1%8B.jpg)

+ Создала сводные таблицы с различными параметрами для построения диаграмм:

  + Круговая диаграмма;
  + Линейчатая диаграмма;
  
![Графики.jpg](https://github.com/LenaMitrofanova/DE-101/blob/main/module1/%D0%93%D1%80%D0%B0%D1%84%D0%B8%D0%BA%D0%B8.jpg) 
  + Картограмма;
  + Гистограмма;
  + График.

![Картограмма.jpg](https://github.com/LenaMitrofanova/DE-101/blob/main/module1/%D0%9A%D0%B0%D1%80%D1%82%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0.jpg)

[Ссылка на дашборд](https://github.com/LenaMitrofanova/Dashboard-Superstore-Exel/blob/main/Sample%20-%20Superstore%20Mitrofanova.xlsx).    
