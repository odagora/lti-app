# LTI - Applicant Tracking System

This project is an Applicant Tracking System (ATS) named 'LTI'. It is built entirely with TypeScript. The Frontend is coded with React, and the Backend uses the Django REST framework. The app utilizes a PostgreSQL database. The backend provides the API endpoints required for the Frontend to render the data. We follow the Domain-Driven Design methodology and the Test-Driven Development approach.

## DDD Backend Folder Structure

The backend is organized into layers following the DDD principles, which help in separating concerns and aligning the software design closely with the domain model. Here's a brief overview of each folder:

- **domain/**: This layer contains the core business logic and domain models. It encapsulates the state and behavior of the business entities.

- **application/**: This layer coordinates the application's tasks. It relies on the domain layer and directs the work that needs to be done, often delegating to the infrastructure layer for implementation.

- **infrastructure/**: Contains implementations of interfaces defined in the application layer, and all external concerns like database access, file systems, and web services.

- **interfaces/**: Typically includes interfaces that define contracts for services, repositories, and other components. In this structure, it is part of the application layer.

This structure supports the separation of concerns and makes the system easier to maintain and evolve.
