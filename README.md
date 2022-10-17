

# Приложение расчета депозита в банке 
Приложение для клиентов банка расчитывает сумму депозитного вклад за определенный период времени. 
Клиенту необходимо ввести:
1. Сумму вклада в рублях.
2. Срок вклада в годах. 
3. Определить тип вклада: вклад с обычным процентом или с капитализацией.

## За функцинал  приложения отвечают следуюшие методы:

Метод
~~~Java 
 double calculateComplexPercent(double amount, double yearRate, int depositPeriod) {}
~~~
принимает на вход три параметра:
1. amount - сумма вклада
2. yearRate - процентная ставка
3. depositPeriod - срок вклада в годах

Вычисляет сумму вклада с обычным процентом.



Метод
~~~Java
 double calculateSimplePercent(double amount, double yearRate, int depositPeriod) {}
~~~
принимает на вход три параметра:
1. amount - сумма вклада
2. yearRate - процентная ставка
3. depositPeriod - срок вклада в годах


   Вычисляет сумму вклада с капитализацией.



