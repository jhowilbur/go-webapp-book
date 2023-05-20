# Go Full Web Application Book



## Introduction

The Book Web Application is a web-based platform created using Golang and several external libraries. It provides users with the ability to browse, search, and manage their collection of books.

Overall, this book web application combines the power of Golang with these external libraries to create a robust and secure platform for managing books. Users can register, login, search for books, add books to their collection, and perform various other operations efficiently and securely.

## Libraries

The application leverages the following libraries to enhance its functionality:

1. github.com/badoux/checkmail: This library enables email address validation, ensuring that users provide valid email addresses during registration and communication processes.

1. github.com/dgrijalva/jwt-go: The jwt-go library is used for JSON Web Token (JWT) handling. It allows the application to authenticate and authorize users by generating and verifying JWTs.

1. github.com/go-sql-driver/mysql: This library provides a MySQL database driver, allowing the application to interact with a MySQL database to store book information, user data, and other relevant details.

1. github.com/gorilla/mux: Mux is a powerful HTTP router and dispatcher for creating RESTful APIs. It is used in the application to define routes, handle HTTP requests, and enable efficient request routing.

1. github.com/joho/godotenv: Godotenv library allows the application to load environment variables from a .env file, facilitating the configuration of sensitive information such as database credentials or API keys.

1. golang.org/x/crypto: The crypto package from the Golang standard library is used for cryptographic operations, such as generating secure hashes or encrypting sensitive data.

1. github.com/gorilla/securecookie: This library provides secure cookie handling, ensuring the integrity and confidentiality of user session data stored in cookies.

## How to run
Inside both folders (webapp and api) edit env file and after run the following command:

```bash
go run main.go
```

#### Note:
The webapp folder is the frontend and the api folder is the backend.

the docker-compose file is for up database online, not to run the application.