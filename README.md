# Secure File Sharing API

Secure file-sharing backend built with FastAPI, featuring JWT authentication, role-based access control, encrypted download links, and file upload workflows.

## Features

* JWT-based authentication using HTTP-only cookies
* Role-based access control for `ops` and `client` users
* Secure file upload workflows
* Encrypted and time-limited download URLs
* File access protection and authorization checks
* Interactive API documentation with Swagger UI
* Included Postman collection for API testing

## Tech Stack

| Category       | Technologies           |
| -------------- | ---------------------- |
| Backend        | FastAPI, Python        |
| Database       | PostgreSQL, SQLAlchemy |
| Authentication | JWT, bcrypt            |
| Validation     | Pydantic               |
| API Testing    | Swagger UI, Postman    |

## User Roles

| Role   | Permissions                                       |
| ------ | ------------------------------------------------- |
| ops    | Upload supported files                            |
| client | Generate secure download links and download files |

## Supported File Types

* `.pptx`
* `.docx`
* `.xlsx`

## API Testing

* Swagger UI available at `/docs`
* Included Postman collection for testing authentication and file workflows

