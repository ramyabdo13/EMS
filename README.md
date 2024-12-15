# EMS - Exam Management System

## Overview

This project is a web application designed to manage exams, questions, and answers. It includes a responsive design with various sections such as a navigation bar, hero section, and services section. The application is built using ASP.NET Core MVC and Entity Framework Core.

## File Structure

- `Controllers/`: Contains the controllers for handling HTTP requests.
  - `HomeController.cs`: Controller for the home page.
  - `QuestionsController.cs`: Controller for managing questions.
- `Models/`: Contains the data models.
  - `Answer.cs`: Model for answers.
  - `EMSDBContext.cs`: Database context.
  - `ErrorViewModel.cs`: Model for error handling.
  - `Exam.cs`: Model for exams.
  - `Question.cs`: Model for questions.
- `Views/`: Contains the Razor views for rendering HTML.
  - `Questions/`: Views related to questions.
    - `Index.cshtml`: View for listing questions.
    - `Create.cshtml`: View for creating a new question.
    - `Edit.cshtml`: View for editing a question.
    - `Details.cshtml`: View for displaying question details.
    - `Delete.cshtml`: View for deleting a question.
    - `_CreateQuestionPartial.cshtml`: Partial view for creating a question.
  - `Shared/`: Shared views and layouts.
    - `_Layout.cshtml`: Main layout view.
    - `_ValidationScriptsPartial.cshtml`: Partial view for validation scripts.
- `wwwroot/`: Contains static files such as CSS, JavaScript, and images.
  - `css/`: CSS files.
    - `site.css`: Main stylesheet.
  - `js/`: JavaScript files.
    - `site.js`: Main JavaScript file.
- `Migrations/`: Contains database migration files.
- `Program.cs`: Entry point for the application.
- `appsettings.json`: Configuration file for the application.
- `appsettings.Development.json`: Development-specific configuration file.
- `EMS.csproj`: Project file for the application.
- `EMS.sln`: Solution file for the application.

## Usage

1. Clone the repository.
2. Open the solution file `EMS.sln` in Visual Studio.
3. Build the project to restore dependencies.
4. Update the connection string in `appsettings.json` to point to your database.
5. Run the application.

## Contributing

Feel free to submit issues or pull requests if you have suggestions or improvements.

## License

This project is licensed under the MIT License.
