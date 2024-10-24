# Submission1
Employee Portal Assessment

# Employee Management System
This is a Mendix application that provides functionality for managing employee records. It includes features like CRUD operations, department hierarchy, and an external weather API integration to display employee location weather.

## Prerequisites
- Mendix Studio Pro Version 10.12.6 or later
- Node.js (only required if you're developing custom widgets)
## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/Mendix-Employee-Management-System.git
   ```

2. Open **Mendix Studio Pro**.

3. In **Mendix Studio Pro**, click **Open App** and browse to the project folder.

4. Run the application locally or deploy to the Mendix cloud.

## Project Structure

- **Domain Model**: Contains entities such as Employee, Department, SubDeparment and WeatherInfo.
- **Microflows**: Key business logic is implemented in microflows like `CreateEmployee`, `UpdateDepartment`, and `FetchWeatherData`.
- **Modules**: The project is divided into module named as :- EmployeeManagement.

  ## Usage

1. After launching the app, log in using the default admin credentials:
   - **Username**: `MxAdmin`
   - **Password**: `1`

2. Navigate to the **Employee Management** section to add, update, or delete employee records.

3. To view weather data for an employee's location, go to the employee's details page, and the weather data will be automatically fetched from the external API based on the employee’s contact information.

   ## External API Integration

The application integrates with the OpenWeather API to fetch weather data based on the employee’s location.

1. To use the weather feature, obtain an API key from [OpenWeather](https://openweathermap.org/).

2. The weather data is fetched when viewing an employee's detail page and is displayed on the same page.

## Features

- CRUD functionality for employee management.
- Department hierarchy with support for sub-departments.
- Integration with OpenWeather API to display employee location weather.
- Sorting and searching functionality on employee lists.

