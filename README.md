Задача №1: проверить XML на Well formed:

<req>

        <surname>Иванов</surname>

        <name>Иван</name>

        <patronymic>Иванович</patronymic>

        <birthdate>01.01.1990</birthdate>

        <birthplace>Москва</birthplace>

        <phone>8 926 766 48 48</phone>

</req> 

Сейчас валидно, ошибка лишь в том что не закрыта


Задача №2: проверить JSON на Well formed:
{

        ""surname"": ""Иванов""

        ""name"": ""Иван""

        ""patronymic"": ""Иванович""

        ""birthdate"": ""01.01.1990""

        ""birthplace"": ""Москва""

        ""phone"": ""8 926 766 48 48""

}

Не валидно, отсутствуют запятые и стоят двойные кавычки
