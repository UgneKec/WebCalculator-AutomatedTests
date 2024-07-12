# WebCalculator-AutomatedTests

Automated tests for a web calculator application using Java, Selenium, Maven, and TestNG. Includes tests for user registration, login, CRUD operations, and authorization.

## Features
- User registration (positive and negative tests)
- User login (positive and negative tests)
- Creating, searching, editing, and deleting records (positive and negative tests)
- Authorization checks to ensure only authorized users can access certain functionalities

## Technologies Used
- Java
- Selenium WebDriver
- Maven
- TestNG

## Setup

### Prerequisites
1. Ensure you have Java, Maven, and a compatible WebDriver installed and configured.
2. Clone and run the web calculator application from [here](https://github.com/algirdaskuslys/testavimui) following the setup instructions provided in its README.

### Clone This Repository
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/WebCalculator-AutomatedTests.git
    ```
2. Navigate to the project directory:
    ```bash
    cd WebCalculator-AutomatedTests
    ```

## Running the Tests

### Using IntelliJ IDEA
1. Open IntelliJ IDEA.
2. Import the project by selecting `Open` and navigating to the cloned repository directory.
3. Ensure the Maven project is fully loaded by selecting `View` > `Tool Windows` > `Maven` and clicking on the refresh icon.
4. In the Project tool window, navigate to `src/test/java/org/example`.
5. Right-click on the test class you want to run (e.g., `CalculatorTest` or `CalculatorTestCase`).
6. Select `Run 'CalculatorTest'` or `Run 'CalculatorTestCase'`.

### Using Eclipse
1. Open Eclipse.
2. Import the project by selecting `File` > `Import` > `Maven` > `Existing Maven Projects` and navigating to the cloned repository directory.
3. Ensure the Maven project is fully loaded by right-clicking the project and selecting `Maven` > `Update Project`.
4. In the Package Explorer, navigate to `src/test/java/org/example`.
5. Right-click on the test class you want to run (e.g., `CalculatorTest` or `CalculatorTestCase`).
6. Select `Run As` > `TestNG Test`.

## Usage
- The tests are structured to run against the web calculator application. Modify the `Main.URL` in the test code if needed to point to your specific instance of the application.

## Notes
- Make sure the web calculator application is fully up and running before executing the tests to avoid any connection issues.
