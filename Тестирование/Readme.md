![image](https://user-images.githubusercontent.com/112687883/213662119-2bf57f64-8ad8-4509-a493-edb9df3e519d.png)
v-модель
интерактивная или инкрементальная модель
![image](https://user-images.githubusercontent.com/112687883/213662490-d0c1c454-cb6f-4279-966c-0444f81ecef7.png)
инкрементная модель-полностью готов отдельных элемент проекта. проблемы возникают при соединении элементов
интеркативная модель-сначала делается набросок всего проекта
потом вносятся доработки
+
1. гибкость в измененияъх
2. учимся на ошибках
3. высокая скорость
-
1. неизвестна стоимость
2. проблемы с архитектурой
трудности тестирования
нет четкого плана для устранения дефектов

Спиральная модель
![image](https://user-images.githubusercontent.com/112687883/213664568-f99a919b-ae6e-40cd-95d0-38e324cb9673.png)
+
управление рисками
-
сложность
проблема тестирования при гибкой или архитектуре

Роль тестирования

независимость тестированияя
разработчтк тестирует свой код
незвисимые тстировщики
независимая команда или группа тестирования
разработчтки тестируют собственный код

команда тестирования
![image](https://user-images.githubusercontent.com/112687883/213667223-d9246700-bca0-43bc-91ec-cb03ec179fb2.png)



Исключения
![image](https://user-images.githubusercontent.com/112687883/229086781-88e8e5df-e5e1-4264-ad30-d32baf8b3acd.png)

Руководитель проекта
сообщать о проблемах проекта, на тормозить развитие проекта




Типы и уровни тестирования

Уровень тестирования
компонентное тестирование
интеграционное тестирование
системное тестирование
приёмочное тестирование
Системное тестирование СБЕРБАНК Онлайн:

Цель: проверить работу приложение на разных версиях андроид(8-12)
Объекты тестирование: телефон, приложение, версия ОС телефона
Документация по тестированию
Вход: включен телефон и найдено приложение в магазине; Выход: тест по критериям
Документ о результатах тестирования
Ручное тестирование на производительность
Метрика - критерии по которым проверяют приложения
Телефон, эмуляторы



классификация тестирования
запуск кода: допуск к коду. 
черный ящик нет доступа, серый-частично и белый-есть
с исполнением и баз инсполнения кода
статическое/динамическое
статическое - ищет дефекты
динамическое - отказ от системы

![image](https://user-images.githubusercontent.com/112687883/215058251-ec4499de-1d1b-42eb-8556-d5d719eb8b0f.png)

варианты

текстовый редактор NOTEPAD
почтовый сервис Mail.ru
гравический редактор Paint
сервис хранения файлов яндекс.диск


таблица:
гравический редактор Paint


лекция 5
тестовые сценарии
тестовый набор: покрытие оператторов и покрытие узлов ветвления(решений)
классы эквивалетности
классом эквивалентности называют множество входных значений, каждое из еоторых имеет одинаковую вероятность обнаружения конткретного типа ошибок. (четные/нечетные числа)

![image](https://user-images.githubusercontent.com/112687883/219609323-9f9f36bf-35ab-46e6-bc1d-846e2253822a.png)


![image](https://user-images.githubusercontent.com/112687883/219617641-022a4aeb-7d1e-42af-9ac5-edd8125be0a9.png)

#include <iostream>

using namespace std;

int main()
{
    cout<<"Hello World";
index = input ("Введите номер: ")
print(index)
a=0
while a != "Все верно":
    while index.isdigit():
        while len(index) != 11:
            indexa = input ("Неверная длина, введите номер: ")
            while index[0] == "0":
                print("Нельзя начать с 0")
        print("Все верно")
        a = "Все верно"
    else:
        index = input("Оставьте цифры, введите номер: ")  
    return 0;
}

Тестовый набор
Тестовая документация
1. план тестирования
https://radar4site.ru/upload/000/u1/4/a/test-plan.pdf
2. https://www.software-testing.ru/images/stories/library/checklist-mobile-app-testen.pdf

критерии приложения  в wpf и android studio:
1. Контролирующие элементы максимально
ненавязчивы (к примеру, исчезают, если не
используются длительное время).
2. Основная функция приложения удобопонятна и
самоочевидна. Было понятно о чем производство
3. Добавьте иконку прогресса ("Загружается…")
для ситуаций с низкой производительностью,
желательно с внятным сообщением.
4. Клавиатура подстраивается под ожидаемый
ввод (к примеру, цифры/буквы).

https://habr.com/ru/post/542422/
https://www.software-testing.ru/images/stories/library/complete-web-application-testing-checklis.pdf
https://checklists.expert/checklist/73222-cheklist-po-igre


https://docs.google.com/document/d/1HOLKqPUAQFTGmtaQGacwKFFMZiCr6q8s/edit#heading=h.gjdgxs



требования к тестировщику по

навыки межличностного общения
умение критиковать и воспринимать критику
оказывать влияние на друших 
вести переговоры


unit test
блок кода, должен проверять одно действие и быть универсальным

свойства:
понятность для пользователей
быстрая работа

Arrange-Act-Assert
предусловие (arrange) - какие у нас переменные и ожидаемый результат
действие (act) - сам тест
постусловие (assert) - верификация результата теста, оформление, читаемость текста и качество документации к тестируемой продукции.


    ![image](https://user-images.githubusercontent.com/112687883/224287279-415195d7-2f89-4ea5-acc9-d434fb47ecb0.png)

![image](https://user-images.githubusercontent.com/112687883/229086961-50048c3d-1a8e-4ace-8744-df6aeeaf1110.png)

public static float Del(float a, float b)
        {
            float del = 0;
            /*if (b == 0)
            {
                Console.WriteLine("Error");
            }
            else*/
            del = a / b;
            return del;
        }

есвсть встроенные ошибки в программу
    пример ошибки
    division by constant zero
    если мы не знаем какая может быть ошибка
    то мы не можем использовать if и else
     в программах есть способы для обработки ошибок, называются исключения
    структура исключения : код, который мы хотим выполнить и поиск ошибок
    
https://vc.ru/dev/137335-unit-testy-na-c?ysclid=lfc5ae2lnm197673354


try new division by constant zero добавление нового искючения

![image](https://user-images.githubusercontent.com/112687883/230592008-628441ea-b9d6-4d73-a2c1-ed8fa72994c2.png)
![image](https://user-images.githubusercontent.com/112687883/230592092-999f2b30-f462-434c-977c-74a214b98dc8.png)
![image](https://user-images.githubusercontent.com/112687883/230592133-314cc7d9-89a8-4d0b-bb2f-c9b4edb38369.png)


    
  сумма тест
    
    using NUnit.Framework;
using Kalkulator;
namespace TestKalkulator1
{
    public class Tests
    {
        [SetUp]
        public void Setup()
        {
        }

        [Test]
        public void Test1()
        {
            float a = 4;
            float b = 10;
            float expected = 14;
            float actual = Class1.Sum(a, b);
            Assert.AreEqual(expected, actual);
        }
    }
}
    
    
    using NUnit.Framework;
using Kalkulator;
namespace TestKalkulator1
{
    public class Tests
    {
        [SetUp]
        public void Setup()
        {
        }

        [Test]
        public void TestSum()
        {
            float a = 4;
            float b = 10;
            float expected = 14;
            float actual = Class1.Sum(a, b);
            Assert.AreEqual(expected, actual);
        }

        [Test]
        public void TestMinus()
        {
            float a = 10;
            float b = 8;
            float expected = 2;
            float actual = Class1.Minus(a, b);
            Assert.AreEqual(expected, actual);
        }
        [Test]
        public void TestUmn()
        {
            float a = 10;
            float b = 10;
            float expected = 100;
            float actual = Class1.Umn(a, b);
            Assert.AreEqual(expected, actual);
        }
        [Test]
        public void TestDel()
        {
            float a = 10;
            float b = 2;
            float expected = 5;
            float actual = Class1.Del(a, b);
            Assert.AreEqual(expected, actual);
        }
        [Test]
        public void TestDel0()
        {
            float a = 78;
            float b = 0;
            float expected = ;
            float actual = Class1.Del(a, b);
            Assert.AreEqual(expected, actual);
        }
    }
}
ТЕСТИРОВАНИЕ ПАРОЛЯ
    

![image](https://github.com/OlgaChubova205/6-semestr/assets/112687883/b942c95b-ebdd-4359-aa7b-867f0a7bb32d)
using Microsoft.VisualStudio.TestTools.UnitTesting;
using Password;
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Password.Tests
{
    [TestClass()]
    public class PasswordChackerTests
    {
        
            [TestMethod()]

            public void Check_PasswordWidthDigits_ReturnsTrue()
            {
                // Arrange.
                string password = "Aq1$";
                bool expected = true;

                // Act.
                bool actual = PasswordChacker.ValidatePassword(password);

                // Assert. 
                Assert.IsFalse(actual);

            }


            [TestMethod()]

           public void Check_PasswordWidthDigits_ReturnsFalse()
            {
                // Arrange.
                string password = "ASDqweASD;";
                bool expected = false;

                // Act.
                bool actual = PasswordChacker.ValidatePassword(password);

                // Assert. 
                Assert.IsFalse(actual);

            }

            [TestMethod()]

           public void Check_PasswordWidthSpecSymbols_ReturnsTrue()
            {
                // Arrange.
                string password = "Aqwe123$";
                bool expected = true;

                // Act.
                bool actual = PasswordChacker.ValidatePassword(password);

            // Assert. 
            Assert.IsTrue(actual);

            }
            [TestMethod()]

            public void Check_PasswordWidth_ReturnsFalse()
            {
                // Arrange.
                string password = "AADqwe123";
                bool expected = false;

                // Act.
                bool actual = PasswordChacker.ValidatePassword(password);

                // Assert. 
                Assert.IsFalse(actual);

            }
            [TestMethod()]

            public void Check_PasswordWidthCaps_ReturnsTrue()
            {
                // Arrange.
                string password = "ASDqwe123$;";
                bool expected = true;

                // Act.
                bool actual = PasswordChacker.ValidatePassword(password);

            // Assert. 
            Assert.IsTrue(actual);

        }



        }
    }

    
    
    
    CLASS 1
    using System;
using System.Linq;



namespace Password
{
    public class PasswordChacker
    {
        public static bool ValidatePassword(string password)
        {
            if (password.Length < 8 || password.Length > 20)
            return false;
            if (!password.Any(Char.IsLower))
                return false;
            if (!password.Any(Char.IsUpper))
                return false;
            if (!password.Any(Char.IsDigit))
                return false;
            if (password.Intersect("#$%^$&_").Count() == 0)
                return false;

            return true;
        }
    }
}






