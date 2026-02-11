# Angular Directives Deep Dive

## About

This is an Angular application built as part of the Angular course by **[Maximilian Schwarzmüller](https://www.udemy.com/user/maximilian-schwarzmuller/)** on Udemy.

The project demonstrates advanced directive concepts including custom structural directives, attribute directives, and permission-based authentication.

## Features

- **Custom Authentication System** - Role-based access control (admin, user, guest)
- **Structural Directives** - Custom directives using TemplateRef and ViewContainerRef
- **Attribute Directives** - Custom directives with host listeners
- **Host Directives** - Directive composition and reusability
- **Permission-based Rendering** - Conditional content display based on user roles

## Technologies

- Angular 18+ (Standalone Components)
- TypeScript
- Angular Signals
- Template-driven Forms
- Custom Directives
- Dependency Injection

## Key Concepts

This project covers:
- Creating custom structural directives
- Using TemplateRef and ViewContainerRef
- Implementing attribute directives with host bindings
- Host directives for directive composition
- Permission-based content rendering
- Angular services with dependency injection
- Signal-based state management
- Authentication flow implementation

## Authentication

The application includes three permission levels:
- **Admin** - Full access (admin@example.com / admin)
- **User** - Regular user access (user@example.com / user)
- **Guest** - Limited access (default)

## Course Author

**Maximilian Schwarzmüller**  
Udemy Instructor

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run development server:
   ```bash
   ng serve
   ```

3. Navigate to `http://localhost:4200/`

## License

This project is part of educational coursework.
