## Overview

A RESTful API service built using Spring Boot to manage the exam enrollment process for a Learning Management System (LMS). The application uses MySQL to persist user data.

## Features

- **CRUD Operations**: Perform Create, Read, Update and Delete operations for Students, Subjects and Exams.
- **Enrollment Logic**: Ensure students can only register for exams after enrolling in corresponding subjects.
- **Exception Handling**: Gracefully handle errors and return appropriate HTTP status codes.
- **GlobalExceptionHandler**: Centralized exception handling using @ControllerAdvice for improved code maintainability.