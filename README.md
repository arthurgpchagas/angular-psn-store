# PSN Web Clone

This project is a simplified replica of the PlayStation Store (PSN) interface, built using Angular. It was developed for study and frontend practice purposes.

## Technologies Used

- **Angular** 14.1.2
- **TypeScript**
- **HTML / SCSS**

## How to Run

Make sure you have **Node.js** and **Angular CLI** installed.

```bash

# Install dependencies
npm install

# Run development server
ng serve
```

Then, open your browser and navigate to: http://localhost:4200

The app supports hot reload: it will refresh automatically when you change any source files.

## Project Structure

```bash
ruby
Copiar
Editar
src/
├── app/
│   ├── components/        # Angular components
│   ├── services/          # Shared services
│   └── app.module.ts      # App module declaration
├── assets/                # Static assets (images, icons, etc.)
└── index.html             # Main HTML file
```

## Testing
You can run unit tests with:
```bash
ng test
```

## Build
To build the project for production:

```bash
ng build
```

The output will be placed in the dist/ folder.

Note: This project was inspired by the PlayStation Store interface and is intended for learning and non-commercial purposes only.
