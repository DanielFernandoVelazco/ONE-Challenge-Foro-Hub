
# Java Backend Forum Project

This is a backend project for a forum application built using Java and Spring Framework.

## Prerequisites

Before running the project, you need to set up the following environment variables:

### Database Configuration:
You will need to configure the following environment variables to set up the MySQL database connection:

- `DB_URL`: The URL for your MySQL database.
- `DB_USERNAME`: Your MySQL database username.
- `DB_PASSWORD`: Your MySQL database password.

### Example of setting environment variables (Linux/MacOS):

```bash
export DB_URL="jdbc:mysql://localhost:3306/your_database"
export DB_USERNAME="your_username"
export DB_PASSWORD="your_password"
```

### Example of setting environment variables (Windows Command Prompt):

```cmd
set DB_URL=jdbc:mysql://localhost:3306/your_database
set DB_USERNAME=your_username
set DB_PASSWORD=your_password
```

## Running the Project

Once the environment variables are configured, you can run the project using the following tools:

### Postman/Insomnia/APIDog:
You can test the API endpoints using Postman, Insomnia, or APIDog. Import the provided collection file to test all the available endpoints.

### Swagger:
This project is also set up with Swagger UI. Once the application is running, you can visit the following URL to explore and test the API via the Swagger UI:

```
http://localhost:8080/swagger-ui.html
```

## Getting Started

1. Clone the repository to your local machine:
    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project folder:
    ```bash
    cd <project-folder>
    ```

3. Build and run the application:
    ```bash
    ./mvnw spring-boot:run
    ```

4. After the application starts, open the Swagger UI or use Postman/Insomnia to interact with the API.

## License

This project is licensed under the MIT License.
