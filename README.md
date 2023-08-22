# Web Application with CRUD Operations (Servlet, JDBC, MySQL)

A web application implementing CRUD (Create, Read, Update, Delete) operations using Java Servlets, JDBC for database interaction, and MySQL for data storage. The application follows the MVC (Model-View-Controller) architecture for a structured and maintainable design.

## Features

- **Create:** Add new records to the database.
- **Read:** Retrieve and display records from the database.
- **Update:** Modify existing records in the database.
- **Delete:** Remove records from the database.

## Technologies Used

- **Java Servlets:** Handling HTTP requests, processing user input, and interacting with the database.
- **JDBC (Java Database Connectivity):** Establishing connections to the MySQL database, executing SQL queries, and managing data retrieval.
- **MySQL Database:** Storing and managing the application's data.
- **MVC Architecture:** Separating concerns into distinct layers for improved maintainability.

## Setup

1. **Database Setup:**
   - Create a MySQL database for the application.
   - Configure the database connection details in `WEB-INF/web.xml` and `WEB-INF/jdbc.properties`.

2. **Build and Deploy:**
   - Build the project using your preferred build tool (e.g., Maven or Gradle).
   - Deploy the application on a servlet container (e.g., Apache Tomcat).

3. **Access the Application:**
   - Open a web browser and navigate to the application URL.
   - Use the provided interface to perform CRUD operations on the data.

## Screenshots
![Screenshot (2034)](https://github.com/thdonadkar/CRUD/assets/72977141/a3da5e0d-d205-4be2-96b5-cf790f706794)
![Screenshot (2035)](https://github.com/thdonadkar/CRUD/assets/72977141/ade6f9f2-48c3-4480-9c21-b770363fa26c)



## Contributing

Contributions are welcome! If you'd like to enhance the application's features, fix issues, or improve the user experience, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add a new feature"`.
4. Push to the branch: `git push origin feature-name`.
5. Create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For inquiries or suggestions, feel free to contact me at thdonadkar413@email.com.
