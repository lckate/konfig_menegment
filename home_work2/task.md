## Вариант 11
Разработать инструмент командной строки для визуализации графа зависимостей, включая транзитивные зависимости.
Сторонние средства дляполучения зависимостей использовать нельзя.  
Зависимости определяются по имени пакета платформы .NET (nupkg). Для описания графа зависимостей используется представление Mermaid. Визуализатор должен выводить результат в виде сообщения об успешном выполнении и сохранять граф в файле формата png.  
Ключами командной строки задаются:  
• Путь к программе для визуализации графов.  
• Имя анализируемого пакета.  
• Путь к файлу с изображением графа зависимостей.  
• Максимальная глубина анализа зависимостей.    
Все функции визуализатора зависимостей должны быть покрыты тестами.  
### Созданный граф
![image](https://github.com/lckate/konfig_menegment/blob/main/home_work2/graph.png)
### Вывод программы
![image](https://github.com/lckate/konfig_menegment/blob/main/home_work2/test_conf2.png)
