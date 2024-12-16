

## 1 АРХИТЕКТУРА
 
 ![image](https://github.com/user-attachments/assets/59023c57-6c8b-488a-b29c-8daf97c57c59)

Рисунок 1.1 – Контейнерный уровень архитектуры

![image](https://github.com/user-attachments/assets/3fedd241-f009-47a2-b647-877ccd0161a5)

Рисунок 1.2 – Компонентный уровень архитектуры

![image](https://github.com/user-attachments/assets/8d94eb63-c573-4ed2-b70b-cc0d60fdb5e6)

Рисунок 1.3 – Схема БД



## 1.1 UML-диаграммы

![image](https://github.com/user-attachments/assets/44744b5e-cc3b-4b37-908a-a96c2fc69a50)

Рисунок 1.4 – Диаграмма классов

![image](https://github.com/user-attachments/assets/93c12072-3db5-404c-bd75-449f35d2d983)

Рисунок 1.5 – Диаграмма компонентов

![image](https://github.com/user-attachments/assets/94dafa53-476e-484d-9781-9f4f392d8ba2)

Рисунок 1.6 – Диаграмма деятельности

![image](https://github.com/user-attachments/assets/a9324493-2c9f-4a61-9bec-52954d696e62)

Рисунок 1.7 – Диаграмма последовательности

![image](https://github.com/user-attachments/assets/83dbe808-4df0-4403-8af5-f5c23c5cba95)

Рисунок 1.8 – Диаграмма вариантов использования



## 2 СИСТЕМA ДИЗАЙНА ПОЛЬЗОВАТЕЛЬСКОГО ИНТЕРФЕЙСА



![image](https://github.com/user-attachments/assets/838dbc61-7264-4237-82d0-c36e13a92bdf)

Рисунок 2.1 – UI Kit программного средства


 ![image](https://github.com/user-attachments/assets/2e7da59b-d98a-4c20-b458-773a78f216f0)

Рисунок 2.2 – Элемент «Кнопка»

 ![image](https://github.com/user-attachments/assets/7541393d-7537-4761-8890-da75aa7905dd)

Рисунок 2.3 – Поле ввода текста


 ![image](https://github.com/user-attachments/assets/dcbc161c-57ac-4309-8639-f43fdcfd1130)

Рисунок 2.4 – Различные элементы управления



![image](https://github.com/user-attachments/assets/94abdce0-7619-462b-89af-ec899622508d)

Рисунок 2.5 – Дропдаун меню


 ![image](https://github.com/user-attachments/assets/3220e400-477a-488d-8f42-135631b1b338)

Рисунок 2.6 – Используемые в программном средстве шрифты

 ![image](https://github.com/user-attachments/assets/b660570e-615c-459c-96d1-f622073bf34c)

Рисунок 2.7 – Цветовая палитра программного средства


![image](https://github.com/user-attachments/assets/921f4b59-5344-4dd8-9ec7-c2380c8ea5c1)

Рисунок 2.8 – Примеры используемых иконок

## 3 ДИАГРАММА КЛАССОВ И ИНТЕРФЕЙСОВ


 ![image](https://github.com/user-attachments/assets/cfa05e5e-b8c4-4fb7-8e1d-2d131eef6b83)

Рисунок 3.1 – Диаграмма классов

## 4 ДОКУМЕНТАЦИЯ 

 ![image](https://github.com/user-attachments/assets/415e02dc-4a89-42e7-b9be-af6824e6d10f)
 ![image](https://github.com/user-attachments/assets/e8c78436-6e15-47d7-9514-5ffe0b1d70a8)
![image](https://github.com/user-attachments/assets/758081c8-db41-4187-92ed-d1529b28748c)
![image](https://github.com/user-attachments/assets/23099dcb-5b3e-4427-bf55-edb58173ff11)
![image](https://github.com/user-attachments/assets/9165e963-b4fd-4bb9-9e5b-84947aa879b4)
![image](https://github.com/user-attachments/assets/359c3ace-88f0-4aeb-9c5b-a7b6a39f71ed)
![image](https://github.com/user-attachments/assets/34c271b2-cb19-4fa7-98c5-6d8fbff5b311)
Ссылка на документацию к API: RiOPK/ApiDocumentation at main · NastaKro/RiOPK

## ПРИМЕРЫ ЭКРАНОВ 
Ссылка на код страницы личный профиль: https://github.com/NastaKro/RiOPK/blob/main/UI
![image](https://github.com/user-attachments/assets/52819e55-107d-4a1b-b6db-c14eb05fa904)

![image](https://github.com/user-attachments/assets/457d478a-9547-4959-98e7-f0b079fd845a)

![image](https://github.com/user-attachments/assets/64303c33-9550-47c5-b43a-2bcbb156ff83)

![image](https://github.com/user-attachments/assets/a4d19c81-3eae-4bec-ac74-98254b45b951)

![image](https://github.com/user-attachments/assets/5a1c37c1-23b9-4979-ad52-9713e85acbed)

![image](https://github.com/user-attachments/assets/06adcde7-099e-4168-9ae7-b2f430523992)

## Тестирование 
Описание: Модульные тесты проверяют отдельные компоненты или функции кода в изоляции от остальной системы. Вот ключевые аспекты и подходы к модульному тестированию:

Тестируемые модули: модульное тестирование проводится на уровне функций, методов или классов. Каждый тест охватывает конкретную функциональность.

Изоляция: для изоляции тестируемого модуля используются заглушки (stubs) и моки (mocks), которые имитируют поведение зависимых компонентов.

Автоматизация: модульные тесты автоматизируются с помощью фреймворков, таких как MSTest, NUnit или xUnit. Это позволяет быстро запускать тесты после каждого изменения в коде.

Методики написания тестов:

Arrange-Act-Assert (AAA): подготовка данных и условий (Arrange), выполнение тестируемого кода (Act) и проверка результатов (Assert).

TDD (Test-Driven Development): методология разработки, при которой тесты пишутся до написания самого кода. Сначала создаются тесты, затем пишется код, который проходит эти тесты.

Интеграционное тестирование (Integration Testing)

Интеграционные тесты проверяют взаимодействие между различными модулями или компонентами системы. Основные аспекты интеграционного тестирования:

Интеграция компонентов: тесты проверяют, как модули взаимодействуют друг с другом, например, взаимодействие между контроллером и базой данных в веб-приложении.

Автоматизация: как и модульные тесты, интеграционные тесты автоматизируются с помощью фреймворков. 

Настройка тестовой среды: интеграционные тесты часто требуют настройки тестовой базы данных и других зависимостей.

Методики написания тестов:

End-to-End (E2E) Testing: проверка всего процесса от начала до конца, включая все взаимодействия.

Mocking and Stubbing: использование моков и заглушек для имитации поведения внешних систем.

ПРИМЕРЫ ТЕСТОВ:

UNIT-ТЕСТ:
using Xunit;

public class AuthorizationServiceTests
{
    [Fact]
    public void Authenticate_ValidCredentials_ReturnsTrue()
    {
        // Arrange
        var service = new AuthorizationService();
        var login = "petrov_admin";
        var password = "petrov_admin";

        // Act
        var result = service.Authenticate(login, password);

        // Assert
        Assert.True(result);
    }

    [Fact]
    public void Authenticate_InvalidCredentials_ReturnsFalse()
    {
        // Arrange
        var service = new AuthorizationService();
        var login = "invalid_user";
        var password = "invalid_password";

        // Act
        var result = service.Authenticate(login, password);

        // Assert
        Assert.False(result);
    }
}
Authenticate_ValidCredentials_ReturnsTrue:
Arrange: Создаем экземпляр сервиса AuthorizationService и задаем валидные учетные данные.
Act: Вызываем метод Authenticate с валидными учетными данными.
Assert: Проверяем, что метод возвращает true.
Authenticate_InvalidCredentials_ReturnsFalse:
Arrange: Создаем экземпляр сервиса AuthorizationService и задаем невалидные учетные данные.
Act: Вызываем метод Authenticate с невалидными учетными данными.
Assert: Проверяем, что метод возвращает false.
Эти модульные тесты помогают убедиться, что метод Authenticate работает правильно для различных сценариев ввода данных.

Интеграционный тест:
using Analytics.Server.Funcs;
using Microsoft.AspNetCore.Mvc.Testing;
using System.Net;
using System.Text;
using System.Text.Json;
using Authorization = Analytics.Server.Objects.Authorization;

namespace Tests
{
    public class AuthorizationControllerIntegrationTests : IClassFixture<WebApplicationFactory<Program>>
    {
        private readonly HttpClient _clientValid;
        private readonly HttpClient _clientNotValid;

        public AuthorizationControllerIntegrationTests(WebApplicationFactory<Program> factory)
        {
            _clientValid = factory.WithWebHostBuilder(builder =>
            {
                builder.ConfigureServices(services =>
                {

                });
            }).CreateClient();

            _clientValid.DefaultRequestHeaders.Add("Cookie", $"{CookiesManager.TOKEN_KEY}={CookiesManager.GenerateToken("petrov_admin", CookiesManager.Roles.ADMIN, 1)}");

            _clientNotValid = factory.WithWebHostBuilder(builder =>
            {
                builder.ConfigureServices(services =>
                {

                });
            }).CreateClient();

            _clientNotValid.DefaultRequestHeaders.Add("Cookie", $"{CookiesManager.TOKEN_KEY}={"123"}");

        }

        [Fact]
        public async Task PostLogin_ReturnOk()
        {
            // Arrange
            var request = new HttpRequestMessage(HttpMethod.Post, "/Authorization");

            var jsonData = new Authorization()
            {
                Login = "petrov_admin",
                Password = "petrov_admin"
            };
            var jsonContent = JsonSerializer.Serialize(jsonData);
            request.Content = new StringContent(jsonContent, Encoding.UTF8, "application/json");

            // Act
            var response = await _clientValid.SendAsync(request);

            // Assert
            Assert.Equal(HttpStatusCode.OK, response.StatusCode);
        }

        [Fact]
        public async Task PostLogin_ReturnUnauthorized()
        {
            // Arrange
            var request = new HttpRequestMessage(HttpMethod.Post, "/Authorization");

            var jsonData = new Authorization()
            {
                Login = "1",
                Password = "2"
            };
            var jsonContent = JsonSerializer.Serialize(jsonData);
            request.Content = new StringContent(jsonContent, Encoding.UTF8, "application/json");

            // Act
            var response = await _clientNotValid.SendAsync(request);

            // Assert
            Assert.Equal(HttpStatusCode.Unauthorized, response.StatusCode);
        }

        [Fact]
        public async Task LogOut_ReturnOk()
        {
            // Arrange
            var request = new HttpRequestMessage(HttpMethod.Delete, "/Authorization");

            // Act
            var response = await _clientValid.SendAsync(request);

            // Assert
            Assert.Equal(HttpStatusCode.OK, response.StatusCode);
        }

        [Fact]
        public async Task LogOut_ReturnUnauthorized()
        {
            // Arrange
            var request = new HttpRequestMessage(HttpMethod.Delete, "/Authorization");

            // Act
            var response = await _clientNotValid.SendAsync(request);

            // Assert
            Assert.Equal(HttpStatusCode.Unauthorized, response.StatusCode);
        }
    }
}

Этот код представляет собой интеграционные тесты для контроллера авторизации в ASP.NET Core приложении. В коде используется тестовый фреймворк xUnit и библиотека Microsoft.AspNetCore.Mvc.Testing для создания тестового веб-приложения.

Описание кода

using-подключения:

using Analytics.Server.Funcs;: Подключение пространства имен для использования функционала Analytics.Server.

using Microsoft.AspNetCore.Mvc.Testing;: Подключение пространства имен для создания тестового веб-приложения.

using System.Net;: Подключение пространства имен для работы с HTTP-запросами.

using System.Text;: Подключение пространства имен для работы с текстовыми данными и кодировками.

using System.Text.Json;: Подключение пространства имен для работы с JSON-данными.

using Authorization = Analytics.Server.Objects.Authorization;: Псевдоним для объекта авторизации.

Пространство имен и класс тестов

Пространство имен namespace Tests содержит класс тестов 

AuthorizationControllerIntegrationTests, реализующий интерфейс 

IClassFixture<WebApplicationFactory<Program>> для создания тестового веб-приложения.

Поля класса

_clientValid: HTTP-клиент, используемый для выполнения запросов с валидным токеном авторизации.

_clientNotValid: HTTP-клиент, используемый для выполнения запросов с невалидным токеном авторизации.

Конструктор класса

В конструкторе создаются два HTTP-клиента:

_clientValid с валидным токеном авторизации.

_clientNotValid с невалидным токеном авторизации.

Методы тестов

PostLogin_ReturnOk: Тестирует успешную авторизацию пользователя с валидными учетными данными.

Создается POST-запрос на /Authorization с валидными данными авторизации.
Ожидается, что статус ответа будет HTTP 200 OK.

PostLogin_ReturnUnauthorized: Тестирует неуспешную авторизацию пользователя с 
невалидными учетными данными.

Создается POST-запрос на /Authorization с невалидными данными авторизации.
Ожидается, что статус ответа будет HTTP 401 Unauthorized.

LogOut_ReturnOk: Тестирует успешный выход пользователя из системы.

Создается DELETE-запрос на /Authorization с валидным токеном.
Ожидается, что статус ответа будет HTTP 200 OK.

LogOut_ReturnUnauthorized: Тестирует неуспешный выход пользователя из системы с невалидным токеном.

Создается DELETE-запрос на /Authorization с невалидным токеном.
Ожидается, что статус ответа будет HTTP 401 Unauthorized.

Этот тестовый класс проверяет основные сценарии авторизации и выхода из системы, обеспечивая таким образом функциональную и интеграционную проверку контроллера авторизации.



using Analytics.Server.Funcs;
using Microsoft.AspNetCore.Mvc.Testing;
using Newtonsoft.Json;
using System.Net;
using Employee = Analytics.Server.Objects.Employee;
using ListSkillsElem = Analytics.Server.Objects.ListSkillsElem;

namespace Tests
{
    public class EmployeeControllerIntegrationTests : IClassFixture<WebApplicationFactory<Program>>
    {
        private readonly HttpClient _clientValid;
        private readonly HttpClient _clientNotValid;

        public EmployeeControllerIntegrationTests(WebApplicationFactory<Program> factory)
        {
            _clientValid = factory.WithWebHostBuilder(builder =>
            {
                builder.ConfigureServices(services =>
                {

                });
            }).CreateClient();

            _clientValid.DefaultRequestHeaders.Add("Cookie", $"{CookiesManager.TOKEN_KEY}={CookiesManager.GenerateToken("petrov_admin", CookiesManager.Roles.ADMIN, 1)}");

            _clientNotValid = factory.WithWebHostBuilder(builder =>
            {
                builder.ConfigureServices(services =>
                {

                });
            }).CreateClient();

            _clientNotValid.DefaultRequestHeaders.Add("Cookie", $"{CookiesManager.TOKEN_KEY}={"123"}");

        }

        [Fact]
        public async Task GetEmployee_ReturnUnauthorized()
        {
            // Arrange
            var request = new HttpRequestMessage(HttpMethod.Get, "/Employee/1");

            // Act
            var response = await _clientNotValid.SendAsync(request);

            // Assert
            Assert.Equal(HttpStatusCode.Unauthorized, response.StatusCode);
        }

        [Fact]
        public async Task GetEmployee_ReturnNotFound()
        {
            // Arrange
            var request = new HttpRequestMessage(HttpMethod.Get, "/Employee/-1");

            // Act
            var response = await _clientValid.SendAsync(request);

            // Assert
            Assert.Equal(HttpStatusCode.NotFound, response.StatusCode);
        }

        [Fact]
        public async Task GetEmployee_ReturnEmployee()
        {
            // Arrange
            var request = new HttpRequestMessage(HttpMethod.Get, "/Employee/1");

            // Act
            var response = await _clientValid.SendAsync(request);

            // Assert
            Assert.Equal(HttpStatusCode.OK, response.StatusCode);

            var responseBody = await response.Content.ReadAsStringAsync();

            var employeeData = JsonConvert.DeserializeObject<Employee>(responseBody);
            Assert.NotNull(employeeData);

            Assert.Equal("Петров", employeeData.LastName);
        }

        public async Task GetEmployeeSkills_ReturnUnauthorized()
        {
            // Arrange
            var request = new HttpRequestMessage(HttpMethod.Get, "/Employee/1/skills");

            // Act
            var response = await _clientNotValid.SendAsync(request);

            // Assert
            Assert.Equal(HttpStatusCode.Unauthorized, response.StatusCode);
        }


        [Fact]
        public async Task GetEmployeeSkills_ReturnNotFound()
        {
            // Arrange
            var request = new HttpRequestMessage(HttpMethod.Get, "/Employee/-1/skills");

            // Act
            var response = await _clientValid.SendAsync(request);

            // Assert
            Assert.Equal(HttpStatusCode.OK, response.StatusCode);

            var responseBody = await response.Content.ReadAsStringAsync();

            var listSkillsData = JsonConvert.DeserializeObject<List<ListSkillsElem>>(responseBody);
            Assert.NotNull(listSkillsData);
            Assert.Equal(0, listSkillsData.Count());
        }

        [Fact]
        public async Task GetEmployeeSkills_ReturnSkills()
        {
            // Arrange
            var request = new HttpRequestMessage(HttpMethod.Get, "/Employee/1/skills");

            // Act
            var response = await _clientValid.SendAsync(request);

            // Assert
            Assert.Equal(HttpStatusCode.OK, response.StatusCode);

            var responseBody = await response.Content.ReadAsStringAsync();

            var listSkillsData = JsonConvert.DeserializeObject<List<ListSkillsElem>>(responseBody);
            Assert.NotNull(listSkillsData);

            Assert.Equal("JavaScript Programming", listSkillsData[0].Name);
        }

    }
}

Интеграционный тест для контроллера EmployeeController
using Analytics.Server.Funcs;
using Microsoft.AspNetCore.Mvc.Testing;
using Newtonsoft.Json;
using System.Net;
using Employee = Analytics.Server.Objects.Employee;
using ListSkillsElem = Analytics.Server.Objects.ListSkillsElem;

namespace Tests
{
    public class EmployeeControllerIntegrationTests : IClassFixture<WebApplicationFactory<Program>>
    {
        private readonly HttpClient _clientValid;
        private readonly HttpClient _clientNotValid;

        public EmployeeControllerIntegrationTests(WebApplicationFactory<Program> factory)
        {
            _clientValid = factory.WithWebHostBuilder(builder =>
            {
                builder.ConfigureServices(services =>
                {

                });
            }).CreateClient();

            _clientValid.DefaultRequestHeaders.Add("Cookie", $"{CookiesManager.TOKEN_KEY}={CookiesManager.GenerateToken("petrov_admin", CookiesManager.Roles.ADMIN, 1)}");

            _clientNotValid = factory.WithWebHostBuilder(builder =>
            {
                builder.ConfigureServices(services =>
                {

                });
            }).CreateClient();

            _clientNotValid.DefaultRequestHeaders.Add("Cookie", $"{CookiesManager.TOKEN_KEY}={"123"}");

        }

        [Fact]
        public async Task GetEmployee_ReturnUnauthorized()
        {
            // Arrange
            var request = new HttpRequestMessage(HttpMethod.Get, "/Employee/1");

            // Act
            var response = await _clientNotValid.SendAsync(request);

            // Assert
            Assert.Equal(HttpStatusCode.Unauthorized, response.StatusCode);
        }

        [Fact]
        public async Task GetEmployee_ReturnNotFound()
        {
            // Arrange
            var request = new HttpRequestMessage(HttpMethod.Get, "/Employee/-1");

            // Act
            var response = await _clientValid.SendAsync(request);

            // Assert
            Assert.Equal(HttpStatusCode.NotFound, response.StatusCode);
        }

        [Fact]
        public async Task GetEmployee_ReturnEmployee()
        {
            // Arrange
            var request = new HttpRequestMessage(HttpMethod.Get, "/Employee/1");

            // Act
            var response = await _clientValid.SendAsync(request);

            // Assert
            Assert.Equal(HttpStatusCode.OK, response.StatusCode);

            var responseBody = await response.Content.ReadAsStringAsync();

            var employeeData = JsonConvert.DeserializeObject<Employee>(responseBody);
            Assert.NotNull(employeeData);

            Assert.Equal("Петров", employeeData.LastName);
        }

        public async Task GetEmployeeSkills_ReturnUnauthorized()
        {
            // Arrange
            var request = new HttpRequestMessage(HttpMethod.Get, "/Employee/1/skills");

            // Act
            var response = await _clientNotValid.SendAsync(request);

            // Assert
            Assert.Equal(HttpStatusCode.Unauthorized, response.StatusCode);
        }


        [Fact]
        public async Task GetEmployeeSkills_ReturnNotFound()
        {
            // Arrange
            var request = new HttpRequestMessage(HttpMethod.Get, "/Employee/-1/skills");

            // Act
            var response = await _clientValid.SendAsync(request);

            // Assert
            Assert.Equal(HttpStatusCode.OK, response.StatusCode);

            var responseBody = await response.Content.ReadAsStringAsync();

            var listSkillsData = JsonConvert.DeserializeObject<List<ListSkillsElem>>(responseBody);
            Assert.NotNull(listSkillsData);
            Assert.Equal(0, listSkillsData.Count());
        }

        [Fact]
        public async Task GetEmployeeSkills_ReturnSkills()
        {
            // Arrange
            var request = new HttpRequestMessage(HttpMethod.Get, "/Employee/1/skills");

            // Act
            var response = await _clientValid.SendAsync(request);

            // Assert
            Assert.Equal(HttpStatusCode.OK, response.StatusCode);

            var responseBody = await response.Content.ReadAsStringAsync();

            var listSkillsData = JsonConvert.DeserializeObject<List<ListSkillsElem>>(responseBody);
            Assert.NotNull(listSkillsData);

            Assert.Equal("JavaScript Programming", listSkillsData[0].Name);
        }

    }
}







 
 
 
 
 
 


