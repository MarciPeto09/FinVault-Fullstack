```markdown
# FinVault

FinVault is a full-stack application designed to securely manage financial documents. It combines a modern web client with a Java Spring Boot API to provide a straightforward way for authenticated users to handle financial files, search for them quickly, preview content, and download or remove documents when needed.

This repository is structured as a multi-project setup:

- FinVault-WEB: the frontend application
- FinVault-API: the backend service and REST API

Together, they form a secure document management workflow for financial records and related files.

## What this project does

FinVault allows users to:

- securely sign in through Amazon Cognito using OAuth 2.0 Authorization Code + PKCE
- authenticate API requests with bearer tokens
- upload financial documents
- search for documents based on relevant information
- preview document content in the browser
- download files when needed
- delete documents from the system
- work with DOCX files using browser-compatible preview rendering

The application is focused on secure, user-friendly handling of financial documentation in a web environment.

## Project architecture

### Frontend
The web app is built with React and Vite and provides the user interface for document management. It interacts with the backend API, handles authentication, and presents file operations in a clean interface.

Key frontend capabilities:
- login and authentication flow
- document search and browsing
- preview support for document types such as DOCX
- file download and deletion actions

### Backend
The API is built with Java and Spring Boot, and it provides the core business logic, authentication integration, and document-related endpoints. It uses Spring Security, JPA, and REST-based services to support the application.

The backend is responsible for:
- secure access control
- API endpoints for document operations
- integration with the frontend client
- managing the application’s service layer and data access

## Tech stack

### Frontend
- React
- Vite
- JavaScript / TypeScript
- DOMPurify
- Mammoth
- Xlsx
- Lucide icons

### Backend
- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- Spring Web MVC / REST
- Maven

## Why this project matters

FinVault is useful for organizations or individuals who need a secure way to manage financial documents without relying on scattered or unmanaged file storage. It brings together authentication, document access control, and document operations in a single application flow.

## Requirements

To run the project, you will typically need:

- Node.js 18+
- npm
- Java
- Maven
- A running FinVault API
- Amazon Cognito configuration for authentication

## Summary

FinVault is a secure full-stack financial document management application that helps users authenticate, manage, preview, search, and organize important financial files. It combines a React frontend with a Spring Boot backend to provide a modern and practical solution for document handling in a secure environment.
```
