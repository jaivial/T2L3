1.	Mostrar les 10 primeres línies
head -n10 passwd

2.	Mostrar les 5 últimes línies
tail -n5 passwd

3.	Mostrar des de la línia 11 fins al final
tail -n +11 passwd

4.	Mostrar de la línia 11 a la 20
tail -n +11 passwd | head -n10

5.	Mostrar el primer byte (caracter) de cada  línia
cut -b1 passwd