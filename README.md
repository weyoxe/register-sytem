# register-sytem
Данный проект был разработан при помощи ASP.NET Identity, который представляет собой встроенную в ASP.NET систему аутентификации и авторизации. Данная система позволяет пользователям создавать учетные записи, аутентифицироваться и управлять учетными записями. 
Класс ApplicationDbContext - контекст данных для работы с Identity. В папке Areas->Identity->Pages можно найти файлы cshtml. И есть некоторые изменения в файле Program.cs.
После создания приложения ASP .Net Core(Model-View-Conroller) был добавилен необходимый функционал  Account/Login и Account/Register, то есть функционал для регистрации и входа в приложение.
В папке Areas/Idenity/Pages/Account находятся Razor-страницы Login и Register, выполняющие соответствующие функции. 
Чтобы все эти станицы могли выполнять свою роль, в классе Program.cs блыла добавлена конфигурация Identity. Настройки подключения с базой данных были заданы в файле appsettings.json в узле ConnectionStrings.
