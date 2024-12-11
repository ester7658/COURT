# Court System - Public Inquiries Platform

## Project Description
מערכת לניהול פניות ציבור ותלונות למערכת בתי המשפט. הפלטפורמה מאפשרת הגשה מקוונת של פניות, תהליך ניהול תלונות ומעקב אחר סטטוס פניות.

## Technologies
### Core Technologies
- Node.js: 18.0.0
- Angular: 16.0.0
- TypeScript: 5.0.0
- RxJS: 7.8.0
- Bootstrap: 5.0.0

### Angular Packages
- @angular/core: 16.0.0
- @angular/common: 16.0.0
- @angular/forms: 16.0.0
- @angular/router: 16.0.0
- @angular/platform-browser: 16.0.0
- @angular/platform-browser-dynamic: 16.0.0

### Development Tools
- Angular CLI: 16.0.0
- npm: 9.0.0
- ESLint: 8.0.0
- Prettier: 2.8.0

## Installation & Setup

### Prerequisites
1. **Node.js**
   ```bash
   # Install Node.js version 18.0.0 or higher
   # Verify installed version
   node --version
   ```

2. **Angular CLI**
   ```bash
   # Install Angular CLI
   npm install -g @angular/cli@16.0.0
   
   # Verify installed version
   ng version
   ```

3. **Bootstrap**
   ```bash
   # Install Bootstrap
   npm install bootstrap@5.0.0
   ```

### Project Setup
1. **Clone Repository**
   ```bash
   git clone <repository-url>
   cd court-project
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Run Development Server**
   ```bash
   ng serve
   ```
   Access the application at: http://localhost:4200

4. **Production Build**
   ```bash
   ng build --prod
   ```

## Project Structure
```
court-project/
├── .git/                               # Git repository
├── .vscode/                            # VS Code configuration
├── node_modules/                       # Dependencies
├── src/
│   ├── app/
│   │   ├── components/
│   │   │   ├── document/
│   │   │   │   ├── document.component.ts
│   │   │   │   ├── document.component.html
│   │   │   │   ├── document.component.scss
│   │   │   │   └── document.component.spec.ts
│   │   │   │
│   │   │   └── sticky-header/
│   │   │       ├── sticky-header.component.ts
│   │   │       ├── sticky-header.component.html
│   │   │       ├── sticky-header.component.scss
│   │   │       └── sticky-header.component.spec.ts
│   │   │
│   │   ├── config/
│   │   │   └── text.config.ts          # Text configurations
│   │   │
│   │   ├── interfaces/
│   │   │   ├── document.interface.ts    # Document type definitions
│   │   │   └── response.interface.ts    # API response types
│   │   │
│   │   ├── services/
│   │   │   ├── document.service.ts      # Document management service
│   │   │   ├── auth.service.ts          # Authentication service
│   │   │   └── api.service.ts           # API communication service
│   │   │
│   │   ├── app.component.ts            # Root component
│   │   ├── app.component.html
│   │   ├── app.component.scss
│   │   ├── app.component.spec.ts
│   │   ├── app.module.ts               # Main module
│   │   └── app-routing.module.ts       # Routing configuration
│   │
│   ├── assets/
│   │   ├── images/                     # Image files
│   │   │   ├── logo.png
│   │   │   └── icons/
│   │   ├── fonts/                      # Font files
│   │   └── i18n/                       # Translation files
│   │
│   ├── environments/
│   │   ├── environment.ts              # Development environment
│   │   └── environment.prod.ts         # Production environment
│   │
│   ├── styles/
│   │   ├── _variables.scss             # SCSS variables
│   │   ├── _mixins.scss               # SCSS mixins
│   │   ├── _reset.scss                # CSS reset
│   │   └── styles.scss                # Global styles
│   │
│   ├── index.html                      # Main HTML file
│   ├── main.ts                         # Application entry point
│   ├── polyfills.ts                    # Browser polyfills
│   └── test.ts                         # Testing entry point
│
├── .gitignore                          # Git ignore rules
├── .editorconfig                       # Editor configuration
├── .
```

@ 2024