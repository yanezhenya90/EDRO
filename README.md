# EDRO:
<br/>

# E - Event
# D - Design
# R - Reality
# O - Objects 
<br/>

### Благословенный.RCe.Framework Precision 0_1 math:
## Как проводить математическиее операции с рядами, начинающимися с 0 и 1?
 В следующих рядах, количество елементов одинаково, но начинаются они с 1 или 0, а потому значение конечного операнда - разное. <br/>
 Больше не надо мучиться. <br/>
 Теперь все математические операции одновременно с двумя рядами, однозначно понятны и видны наглядно. <br/>
 Мы объявили эти ряды, в стиле Благословенный.RCe.Framework Precision 0_1 math: <br/><br/>
 
 ## Объявляем префикс "int0", для ряда начинается с 0:
 int0_name - integer started from 0 (0,1,2,3,4,5)=5;<br/><br/>
 
## Объявляем префикс "int1", для ряд начинается с 1:
 int1_name - integer started from 1 (1,2,3,4,5,6)=6;<br/>
<br/>

### Приведение типов:
int0_name+1 = int1_name; <br/>
int1_name-1 = int0_name; <br/><br/>
Лучше, чтобы не путаться предворительно привести все типы к INT1; <br/>
<br/>

### Сложение: 
1.Предворительно приведём все типы к INT1;<br/><br/>
((int0_name+1)+int1_name)     =int1_result;<br/>
<br/>

### Преобразование в нужный формат:
(int1_result - 1)             = int0_result; <br/>
<br/>

### Сравнение: 
 <br/>
(int0_name+1)    >|<|==|!=    int1_name; <br/>
<br/>

### Деление: 
1.Приведём все данные к типу INT1.<br/>
(int0_name+1)/int1_name       =int1_result; <br/>
<br/>

### И приведение типа к нужному:
int1_result-1                 =int0_result; <br/>
<br/>

### Умножение: 
1.Приведём все данные к типу INT1.<br/><br/>
int1_name*(int0_name+1)       =int1_result; <br/>
<br/>

## Это гениально! Экономит миллионы лет, на любом языке программирования и просто в устном счёте.
<br/>

## Благословенный.RCe.Framework Precision 0_1 math!
# PM01
<br/>

###   Автор: A.A.Chekmarev: assminog@gmail.com. 
