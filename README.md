Todo Management Application is a Spring Boot -React Full stack Application architecture. It manages the list of Todo's based on roles like user and admin. 

Requirements:  
 - Build REST API's for Todo Management Module (Add, Get, Get all, update, delete, complete, incomplete)
 - Build Frontend React app to consume rest api's to perform operations like (add new todo, list all todos, update particular todo, delete tood, mark todo complete or incomplete)
 - Secure all REST API's  using spring security and implement role based authorization
 - Build Register and Login REST API's
 - Build frontend for register and login rest api's to perform operations like register todo, login to todo app, logout.
 - Secure rest api's using JWT(Json web token)




Tech Stack used:  
1. Spring Boot - Spring Boot provides a simplified approach to developing Java applications by leveraging the Spring framework. It also includes built-in autoconfiguration capabilities that initialize applications with pre-set dependencies to help avoid errors. Used to develop restful api's. Spring initializer is a web tool used to create spring boot application with required dependencies.
2. Spring Data JPA Hibernate - JPA(Java persistance api) is a standard way of interacting with daatabases in java. Provides object relational mapping (ORM) allows to map java objects to DB tables. Spring Data Jpa is a module in spring framework that spimplifies working with jpa. Hibernate is populat implementation of JPA. Open source framework orm implements jpa interfaces and provides additional features beyond jpa standard. Spring data jpa builds in top of hibernate provides high level abstraction. Renders boilerplate code required for data access. Provides features like repository interfaces, query methods, transaction management.
3. My SQL Database
4. IntelliJ IDEA
5. Maven - Build Tool
6. Postman Client - Test the REST API's
7. React JS - JS library build
8. Vite JS
9. Bootstrap CSS - styling css
10. JavaScript
11. NPM- a library and registry for JavaScript software packages
12. VS Code
13. Axios
14. Spring Security - Spring Security is a framework which provides various security features like: authentication, authorization to create secure Java Enterprise Applications. It is a sub-project of Spring framework
15. JWT - JSON Web Token is an open industry standard (RFC 7519) used to share information between two entities, usually a client (like your app's frontend) and a server (your app's backend). They contain JSON objects which have the information that needs to be shared.
    


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
