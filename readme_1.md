# Домашнее задание по Модулю 1: Роль Аналитики в Организации

Для лучшего понимания особенностей работы с данными, разнообразия профессий и областей применения, я прошла Track в DataCamp [Understanding Data Topics](https://app.datacamp.com/learn/skill-tracks/understanding-data-topics).<br>



## Установка GIT и GitHub
1. Для получения базовых знаний при работе в командной строке - курс [Introduction to Shell](https://app.datacamp.com/learn/courses/introduction-to-shell) в DataCamp.
1. Для основ работы в гите помог [Introduction to Version Control with Git](https://app.datacamp.com/learn/courses/introduction-to-version-control-with-git).
1. На мой взгляд, самое удачное видео на YouTube для новичков [GIT - Полный Курс Git и GitHub Для Начинающих [4 ЧАСА]](https://www.youtube.com/watch?v=O00FTZDxD0o).

 ## Архитектура Аналитического Решения

Для построения верхнеуровневой архитектуры аналитического решения использовала программу draw.io.
  
  Архитектура аналитического решения выполнена для электросетевой компании. В которой информация поступает непосредственно с оборудования (IoT), и напрямую заводится в систему персоналом. 
  
  Имеются два вида потребителей информации: **бизнесс-менеджеры** , принимающие финансовые решения,  и **инженеры**, анализирующие параметры оборудования и принимающие решения по изменению режима энергосети. 

![Аналитическое решение](https://github.com/LenaMitrofanova/DE-101/blob/main/module1/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B5%20%D1%80%D0%B5%D1%88%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%81%D0%B5%D1%82%D0%B8.jpg)

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

[Ссылка на дашборд](https://github.com/LenaMitrofanova/DE-101/blob/main/module1/Sample%20-%20Superstore%20Mitrofanova.xlsx).    


