# Альмухаметов Тимур - "Менеджер паролей"
# Пользовательские сценарии 

### Группа: 11 - МИ - 1
### Электронная почта: almukhametov07@mail.ru


### [ Сценарий 1 - Регистрация пользователя ]

1. Пользователь запускает программу и видит предложение создать пользователя
1. Пользователь вводит логин, с которым он будет заходить в систему
2. Пользователь вводит пароль, с которым он будет заходить в систему
3. Пользователь повторно вводит пароль
4. Если выбранный логин уже существует в системе, то пользователю сообщается об этом и предлагается придумать новый логин
5. Если пароль содержит менее 6 символов, система сообщает, что пользователь должен придумать новый пароль
8. Если все введённые данные соответствуют требованиям регистрации, то система создает аккаунт пользователя

### [ Сценарий 2 - Добавление пароля ]

1. Пользователь нажимает кнопку добавить пароль
2. Пользователь вводит сайт
3. Пользователь вводит логин от этого сайта 
4. Предлагается сгенерировать пароль 
5. Если пользователь выбрал сгенерировать, то он показывается пользователю и вносится в базу
6. Если пользователь ввел свой пароль, то он проверяется на сложность
7. Если пароль простой, то пользователь будет оповещен
8. Пользователю предлагается проверить введенные данные 
9. Пароль вносится в базу данных и шифруется внутри нее
10. Пароль виден в базе на главном экране

### [ Сценарий 3 - Предложение пароля ]

1. Пользователь находится на сайте 
2. Пользователь выбирает залогиниться на сайте
3. У пользователя запрашивается логин или пароль
4. Если пароль сохранен, то он автозаполняется или предлагается
5. Если пароля нет, то предлагается его заполнить в базу
6. Пользователь нажимает продолжить
7. Пользователь логинится на сайте 

### [ Сценарий 4 -  Вход в профиль пользователя]

1. При запуске программы у пользователя запрашивается логин и пароль
2. Пользователь вводит логин 
3. Пользователь вводит пароль
4. Если профиль существует и пароль подходит, то пользователь логинится
5. Если данные не подходят, то выводится соответствующая надпись
6. Если данные не подходят 5 раз подряд, то предлагается создать другой аккаунт
7. Если пользователь не смог ввести пароль 10 раз подряд, то данные уничтожаются

### [ Сценарий 5 - Удаление пароля из базы ]

1. Пользователь заходит на главный экран
2. Пользователь видит свой список паролей
3. Пользователь выбирает какой пароль удалить 
4. Перед пользователем вылазит уведомление об уверенности своих намерений 
5. Если пользователь соглашается, то он переходит к пункту 7
6. Если пользователь не соглашается, то он возвращается к списку паролей 
7. Пароль удаляется из базы и с главного экрана 

### [ Сценарий 6 - Своевременная смена пароля ]

1. Пользователь добавил новый пароль
2. Пользователь отметил галочку об оповещении
3. Спустя 3 месяца, ему приходит уведомление о необходимости смены пароля
4. Либо пользователь соглашается и переходит к пункту 6
5. Либо отказывается и переходит к пункту 7
6. Пользователь меняет пароль 
7. Пароль не меняется и остается таким же 
8. Через еще 3 месяца снова приходит уведомление о смене пароля

### [ Сценарий 7 - Изменение пароля ]

1. Пользователь изменил пароль на каком-нибудь сайте
2. Решил поменять его и в менеджере
3. Пользователь ищет нужный пароль в списке паролей 
4. Пользователь нажимает кнопку для его изменения 
5. У пользователя запрашивается новый пароль 
6. Пользователь вводит новый пароль 
7. Пользователь вводит новый пароль второй раз
8. Пароль изменяется в профиле 





















