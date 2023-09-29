# Lost and Found Posting Website

This is a simple web application for creating lost and found posts. Users can submit information about lost or found items, including a name, location, description, contact details, and an optional image.

## Features

- Post lost or found items without the need for user registration
- Upload an image along with item details
- View and manage posted items

## Technologies Used

- HTML
- PHP
- MySQL

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/lost-and-found-website.git
    ```

2. Set up your MySQL database by running the provided SQL script.

3. Configure the database connection in `post_handler.php` with your credentials:

    ```php
    $servername = "your_server_name";
    $username = "your_username";
    $password = "your_password";
    $dbname = "your_database_name";
    ```

4. Create an `uploads` folder in your project directory for storing uploaded images.

5. Open the project in a web server environment (e.g., XAMPP, MAMP) or upload it to a hosting provider.

6. Access the application in your web browser.

## Structure

- `index.html`: Front-end HTML form for submitting lost and found posts.
- `post_handler.php`: PHP script for handling form submissions and interacting with the database.
- `uploads/`: Folder to store uploaded images.
- `README.md`: Project documentation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was created as a learning exercise.
- Feel free to contribute and improve the application!

