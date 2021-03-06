## Призачення документу
Даний документ створений для детального опису продукта, бізнес-моделей і політики взаємодії з користувачем. У розділі "Сценарії" описані основні функціональності продукту. Діаграми юзкейсів і бізнес-моделей відображають взаємодії користувача із системою і окремих частин системи один з одним.
## Зміст
1. Вступ

           1.1 Мета

2. Короткий огляд продукту

           2.1 Призначення системи управління

           2.2 Політика взаємодії з користувачем

           2.3 Характеристика ділового процесу

           2.4 Сценарії

3. Діаграми

           3.1 Діаграма юзкейсів

           3.2 Діаграма бізнес-моделей

## 1. Вступ
Система управління проектами - комплекс програмного забезпечення, що буде включати в себе програми для планування завдань, складання розпису, контролю ціни і управління бюджетом, розподілу ресурсів, спільної роботи, спілкування, швидкого управління, документування та адміністрування системи, які будуть об'єднані в веб-сервіс "TaskShot". Разом з тим, веб-сервіс буде мати також додаток на телефони з операційною системою Android та IOS.

Більш детально ознайомитися з принципами ведення розробки на проекті можна в документі [Description](https://github.com/averkova-a/OBD_project/blob/master/Main/Description.md)
## 1.1. Мета
Метою проекту є створення системи управління проектами за допомогою якої  можна краще керувати проектом, розподіляти кошти та час. Також система допоможе підвищувати точність планування проектів, розподіл завдань між співробітниками.
## 2. Короткий огляд продукту
  Команда розробників має на меті розробити сервіс "TaskShot" -  систему управління проектами.

  Дана система надаватиме змогу управляти та планувати проектами. Продукт покликаний на підвищення ефективності та продуктивності командної роботи над проектами. TaskShot дозволятиме легко та швидко управляти ресурсами: часом, задачами та їхніми пріоритетами. Також сервіс дозволятиме надавати користувачам різні ролі та управляти правами доступу. Даний сервіс розрахований на середньо-великі команди.
  Система TaskShot буде складатися з:
   - сайту для користувачів;
   - програмного додатка для смартфонів на базі Android, IOS.  

TaskShot складатиметься з інтуїтивно зрозумілого інтерфейсу з підтримкою інтернаціоналізації. Сервіс коштуватиме 4$/місяць при річній оплаті на користувача. Доступ до системи матимуть зареєстровані користувачі.

## Призначення системи управління
Для швидкого і зручного управління ресурсами, артефактами та доступу до розширеної статистики прогресу розробки.
Особа отримує можливість ефективного управління командою розробки, гнучкого налаштування прав учасників проекту, створення особистих шаблонів артефактів, ролей і плана розробки.

## Політика взаємодії з користувачем
Система допоможе розподілити обов'язки і позначити пріоритети.

Користувач системи може, згідно встановлених менеджером правил, отримувати інформацію щодо проекту, а також редагувати і доповнювати її за необхідності.
Користувач, завдяки системі, може легко взаємодіяти з командою та керувати необхідними для проекту файлами.

Існує декілка груп користувачів: <br>
**Користувач** - особа, що не має активного профілю в системі. <br>
**Зареєстрований користувач** - особа, що має активний профіль в системі. <br>
**Учасник проекту** - зареєстрований користувач, який був запрошений до проекту і прийняв запрошення. <br>
**Менеджер проекту** - зареєстрований користувач, який створив власний проект. <br>


## Характеристика ділового процесу
Менеджер розподіляє обов'язки між підлеглими. Кожен Учасник виконує завдання, які були призначені йому. 


Менеджер розподіляє  можливості і права кожного учасника проекту за допомогою ролей. Ролі визначають які дії може виконувати Учасник з артефактами на проекті. Ролі можуть бути взяти з вже існуючого набору, який надає система, або створені з нуля Менеджером. Менеджер повинен визначити роль кожного учасника на проекті. Одна роль може бути видана декільком Учасникам, також один Учасник може мати декілька ролей.

## Сценарії
Опис взаємодії системи та користувача. Переглянути усі сценарії можна за посиланням: [Use Cases](https://github.com/averkova-a/OBD_project/tree/master/Main/Use%20Cases)


## Діаграми юзкейсів (доповнюється)

![Діаграма користувачів](https://github.com/averkova-a/OBD_project/blob/master/Main/UC-Diagram/Users.png)


Діаграма дій зареєстрованого користувача
![Діаграма дій Зареєстрованого користувача](https://github.com/averkova-a/OBD_project/blob/master/Main/UC-Diagram/LoginUser.png)


Діаграма дій учасника проекту
![Діаграма дій Учасника проекту](https://github.com/averkova-a/OBD_project/blob/master/Main/UC-Diagram/ProjectUser.png)


Діаграма дій Менеджера
![Діаграма дій Менеджера](https://github.com/averkova-a/OBD_project/blob/master/Main/UC-Diagram/Manager.png)


Розширення для "Керування артефактами"
![Розширення для "Керування артефактами"](https://github.com/averkova-a/OBD_project/blob/master/Main/UC-Diagram/Artefacts.png)
## Діаграма бізнес-сутностей
![Діаграма бізнес-сутностей](https://github.com/averkova-a/OBD_project/blob/master/Main/UC-Diagram/BusinessEntity.png)


## Діаграма класів
![Діаграма класів](https://github.com/averkova-a/OBD_project/blob/master/Main/UC-Diagram/ClassDiagram.png)


## Діаграма EER 
![Діаграма EER](https://github.com/averkova-a/OBD_project/blob/master/Main/UC-Diagram/eer.png)

