LK1
История операционных систем
ЭВМ 1го поколения - ОС пока не существует
1943 год - устройства для расчета баллистической таблицы
ЭНИАК - первый электронный дифференциальный анализатор(цифровой вычислитель)

Особенности:

использавание ламп(греются и горят)
возможность перепрограммирования
используются перфокарта
Недостатки:

для решения диф. уравнений ~ 1 млн перфокарт(перепрограммирование 2+ дня)
Архитектура фон Неймана
Особенности:

переход на двоичную систему (есть сигнал - 1; нет сигнала - 0)
уходят от перфокарт, память состоит из пронумерованных ячеек
Программа - последовательность команд, выполняются одна за другой.
image

ЭВМ 2го поколения
Плюсы:

нет тепла, нет перегорания -> надёжно
маленький размер, плотная компановка -> ЭВМ меньше
Недостатки:

сложная диагностика
дорогое производство
Появление алгоритмических языков (COBOL, ALGOL)
Появление компиляторов -> появление программистов
Пакетная обработка данных - задачи сменяются не вручную, а подаются на вход пачкой

второе поколение ЭВМ
пакетная обработка заданий, формализованный язык управления заданиями

ЭВМ 3-4го поколения
большие интегральные схемы 10 000 000 операций в секунду
3.
Плюсы интегральных схем:
- автоматизация производства, уменьшение стоимости
Многозадачность, принцип разделения времени
4.
- многозадачность
-Появление виртуальной памяти
появляются Apple и Unix
-принцип разделения времени
-база данных

Linux
в 80-ые годы появление протокола TCP/IP (Транспортная сеть-протокол, или протокол передачи данных) Этот протокол определил, что инфорпмация дробится на пакеты , у каждого из которых есть уникальный номер, что позволяет отслеживать их передачу.

Линус Торвальдс(1991)
-Утилиты: gcc, bash
-появление системных вызовов UNIX
-монолитное ядро

Функции операционной системы:
-обеспечение выполнения программы
-сколько памяти выдано
-обработка системных вызовов
-ввод и вывод данных
-организация доступа к устройствам посредством файловых систем
-обеспечение безопасности
-организация сетевого стека
-стандартизированный доступ к устройствам ввода-ввывода
-управление памятью системы(выделение, освобождение)

![image](https://user-images.githubusercontent.com/112687883/213100939-2fd5e7a1-22ac-4528-93a0-c47d8b8dde96.png)

Микроядерная архитектура

![image](https://user-images.githubusercontent.com/112687883/213101270-8ff5ca20-588b-44a9-8a27-7f60ce6b0627.png)

Совместимость ОС
Двоичная запуск экзе файла
На уровне исходных кодов передается файл с кодом

![image](https://user-images.githubusercontent.com/112687883/213102111-be3a32cf-0c6d-4976-ad3d-966898df2b86.png)


Особенности
в Unix все есть файл
(клавиатура, флэшка)

Типы файлов
1) Символьные устройства(клавиатура или любое устройство ввода)
2) Блочные устройства(дисковвод, флэшки, диски)
3) Каталоги(папки, директории)
4) Ссылки(ярлык)
Устройства связи
5) Именованные каналы(то, по чему идет связь)
6) Сокеты(узлы связи)

https://user-images.githubusercontent.com/112687883/215970735-51a92768-f1c4-4273-9a73-ec8d67fdb62f.png



защита 1 задания
ls (позволяет посмотреть, какие пап вам доступны)умолчанию
cd 'Рабочий стол' (позволяет перейти в папку, где лежит Ваш код),
gcc Hello.c -o test (компилирует вашу программу в файл с именем test (имя можно менять). /test (запуск кода).

GCC - GNU Compiler Collection - набор компиляторов и сопутствующих утилит, GCC входит в состав любого дистрибутива Linux и, как правило, устанавливается по умолчанию. 
a.out - имя обозначало assembler output



защита 2 задания 
1. что такое $?
это ввод команды от непривилеригорованного пользователя
команда: порядок данных, которые мы ищем (в нашем случае)

2. что такое inot?
это iD

3. что такое echo
как print вывод информации

4. что делают каналы?



5. в чем разница каналов и сокетов
каналы это процессы
а сокеты между процессами

ЛК4
Потоки ввода, ввывода:

STDIN(0)-стандартный ввод, файл из которого осуществляется чтение

STDOUT(1)-стандартный вывод,файл в который осуществляется запись

STDERR(2)-стандартный поток ошибок,файл в который осуществляется запись сообщений об ошибках

перенаправление ввода command<filename
                                       $cat<in_example_1
                                       $./input2.sh<in_example_1&
command>filename-rewrite 

command>>filename-append

2>/dev/null-заглушить STDERR

Процессы и потоки

Процесс- это набор ресурсов задачи во время ее выполнения:

память,открытые файловые дескрипторы,контекст выполнения,обработчики сигналов,как минимум один поток,pid.

Потоки имеют общую виртуальную память
![image](https://user-images.githubusercontent.com/97913101/217463528-2a542ee2-a12e-4b0e-80d2-84e1dd1a3d71.png)
![image](https://user-images.githubusercontent.com/97913101/217463614-77199431-5df1-418b-a191-2810b2cba61f.png)
![image](https://user-images.githubusercontent.com/97913101/217464165-6d1bed1c-b578-47fe-9ced-ba37b0970387.png)
![image](https://user-images.githubusercontent.com/97913101/217464282-4fc0acf4-0922-4525-ba75-a5f9f6ff1a97.png)
![image](https://user-images.githubusercontent.com/97913101/217464430-51d25537-4bd2-4df5-aa58-e63a835aa843.png)
![image](https://user-images.githubusercontent.com/97913101/217464751-3166bb10-9f3f-46ea-a26f-3b4496bc0229.png)
Жизненный цикл процесса
![image](https://user-images.githubusercontent.com/97913101/217466133-deac82ce-741a-44fb-baf7-01dca5010225.png)

Появление процесса в системе 
unit-создание процесса
fork()-коппирование процесса
есть дочерний и родительский процесс,дочерний процесс полная копия родительского но в первом получает управление,а его pid приписывается родительскому процессу
совместное адресное пространство copy-on-write
![image](https://user-images.githubusercontent.com/97913101/217467512-ff8cced2-42b9-4da1-9f7e-57b2d1e7bf32.png)
Смерть процесса:
exit(kill) или сигнал завершения 
По завершении, дочерний процесс переходит в состояние зомби
$ хранит код завершения последней команды
![image](https://user-images.githubusercontent.com/112687883/230008806-09abce9e-90b7-47f5-ac67-7ff859cfdf33.png)
![image](https://user-images.githubusercontent.com/112687883/230008839-e5f1c77f-e105-4e29-8863-71d5d934618b.png)

задание 2.

работа с файлами

Операция: создать, написать, прочитать, удалить, проверить 
![image](https://user-images.githubusercontent.com/97913101/216910008-bd60cfd0-71fb-4076-9447-9d4935830ab1.png)
![image](https://user-images.githubusercontent.com/97913101/216910081-7dc67bf2-3833-4044-bbf1-11c541b19621.png)
![image](https://user-images.githubusercontent.com/97913101/216910134-978aa7b9-fc33-4e7d-9251-771448b42919.png)

Задание 3

![220560365-057c1556-6f80-4130-b45c-4a75f393f238](https://github.com/Varya2018/6sem/assets/97594244/ebe1499e-5719-41e1-bb45-a9c0e7bea252)
![220555743-d0e4094c-97b4-4759-ac49-6ff290c6ffcb](https://github.com/Varya2018/6sem/assets/97594244/2593ebfd-9538-4b75-bcb5-cd8f59d72e47)
![220555968-0830d4d7-5166-4df2-9bb9-7c479a47df21](https://github.com/Varya2018/6sem/assets/97594244/fae215c1-cd2e-45a5-a009-c0877963612a)
![220556373-eaffc2f4-d22e-40cb-ab9d-96c022e2ba98](https://github.com/Varya2018/6sem/assets/97594244/9118dcb8-d9e8-4356-ab6f-d0278a1c3da7)
![220559314-d2df56e3-bac1-493e-8c88-57ff7a24153e](https://github.com/Varya2018/6sem/assets/97594244/c734e0cd-c107-4c12-ad75-4b56132217fd)
![220559226-3d182eb4-2a9a-4b06-87aa-8cdc1621434f](https://github.com/Varya2018/6sem/assets/97594244/3e0b7999-1575-4802-9274-840075b03505)
![220559113-87479d2c-3c6b-462a-8bb3-4f6de4ea8c9c](https://github.com/Varya2018/6sem/assets/97594244/17f9f9e5-89bd-4290-8887-52069aa9d5bb)

Задание 4

![222062860-a3f7b5a1-a010-4c40-8164-5af73f540a3e](https://github.com/Varya2018/6sem/assets/97594244/47820a31-ac4d-4075-803e-a6fe7cf2486c)
![222062863-c30b4221-ea0b-43f1-be56-8ec21d5edc09](https://github.com/Varya2018/6sem/assets/97594244/e5ec2c10-3362-48d1-be6b-0807853c254c)
![222062865-5e1e5d41-daac-4ee9-a642-4c12b59816d5](https://github.com/Varya2018/6sem/assets/97594244/40edb22d-7639-4daf-b017-7a531be83ca3)
![222062867-5069a5ef-51ce-4cbf-9dbf-870bc441c845](https://github.com/Varya2018/6sem/assets/97594244/c1357396-c737-4ded-bcef-cae486ce33f9)


Ready - процесс готов к выполнению, они ждут процессорное время
Running - выполняется весь квант времени, либо пока не будет вытеснен более приоритетной задачей. Остановленный процесс(Stopped)

Задение 5

![Screenshot_43](https://github.com/Varya2018/6sem/assets/97594244/88de16b2-c834-40d7-b54c-7974ce4ecfba)
![Screenshot_44](https://github.com/Varya2018/6sem/assets/97594244/2269d332-9c23-4046-8179-21acddd6db65)
![Screenshot_45](https://github.com/Varya2018/6sem/assets/97594244/60a4e747-f780-4059-b067-6e7bad7eae49)
![Screenshot_46](https://github.com/Varya2018/6sem/assets/97594244/f0e9aef3-9834-4d50-9bb2-9234a222fa70)
![Screenshot_47](https://github.com/Varya2018/6sem/assets/97594244/9ce10109-c3a6-4d1b-83b5-2d9396f0a6dd)
![Screenshot_48](https://github.com/Varya2018/6sem/assets/97594244/2e359060-dcbf-460d-b420-fde051b7a30f)
![Screenshot_49](https://github.com/Varya2018/6sem/assets/97594244/a90be2aa-667f-4ac7-9e1c-74fd63318571)
![Screenshot_50](https://github.com/Varya2018/6sem/assets/97594244/a7a44bb9-57a3-4f95-9d69-f1b683f28d00)
![Screenshot_51](https://github.com/Varya2018/6sem/assets/97594244/8faf7364-8015-4b18-a0a9-3946d9bf3ac8)
![Screenshot_52](https://github.com/Varya2018/6sem/assets/97594244/05e9df8c-095c-4f9f-a76e-5216b921eb1f)
![139705761-fe527094-819e-4bbd-abfc-451ca3198360](https://github.com/Varya2018/6sem/assets/97594244/13e2b868-8aae-45f6-8e59-1e16ba602b9e)



Задание 6
![Screenshot_21](https://github.com/Varya2018/6sem/assets/97594244/aa195226-bf0c-467e-b9bd-a1e0fb9242ee)
![Screenshot_22](https://github.com/Varya2018/6sem/assets/97594244/1f8d3cca-2602-4a09-993d-f9700eba66a4)
![Screenshot_23](https://github.com/Varya2018/6sem/assets/97594244/2d105e2b-e7a0-4ed0-85a2-4cd4d59fba5b)
![Screenshot_24](https://github.com/Varya2018/6sem/assets/97594244/c71e83bb-1b68-4d85-91b3-7c89d5b05e5c)
![Screenshot_25](https://github.com/Varya2018/6sem/assets/97594244/77db32fe-8a5d-45cc-8a25-629d4716d0b8)
![Screenshot_26](https://github.com/Varya2018/6sem/assets/97594244/70aa5b3e-1b0d-4fc2-a564-388c63e4288d)
![Screenshot_27](https://github.com/Varya2018/6sem/assets/97594244/3998972b-bc93-46d3-83e5-3673b9b64e67)
![Screenshot_33](https://github.com/Varya2018/6sem/assets/97594244/fa998234-5371-4c12-a1c0-7ca9388c81ca)
![Screenshot_34](https://github.com/Varya2018/6sem/assets/97594244/143598b4-b609-4a1d-8e4a-72efc1f2eef1)
![Screenshot_35](https://github.com/Varya2018/6sem/assets/97594244/55ef405b-65a7-4271-9983-25156d4bd1b9)
![Screenshot_36](https://github.com/Varya2018/6sem/assets/97594244/40f7e664-4b13-43c3-aa6a-56e2128b76c6)
![Screenshot_37](https://github.com/Varya2018/6sem/assets/97594244/43b00860-44c8-43fe-b6bd-679041649055)
![Screenshot_38](https://github.com/Varya2018/6sem/assets/97594244/9990f92f-6cd6-47ad-a49a-1a46138f7eaa)
![Screenshot_39](https://github.com/Varya2018/6sem/assets/97594244/79bddc14-f20a-47a8-866e-c81f38e99c17)
![Screenshot_41](https://github.com/Varya2018/6sem/assets/97594244/7a7ccdf6-64b9-473c-8133-7ec7c7b3d27a)
![Screenshot_42](https://github.com/Varya2018/6sem/assets/97594244/154088d0-0295-4056-936c-6428b2fb72d8)

