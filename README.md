# Unnathi Guidance Cell

This project is a browser-based student application and record management app for the Unnathi Guidance Cell.

## Features

- Create, update, and manage student applications
- Save student data locally in the browser
- Upload and manage documents
- Search and filter student records
- Export backup JSON and CSV data
- Print application records

## Run locally

```bash
npm install
npm run dev
```

Then open the local Vite URL shown in the terminal.

## Production build

```bash
npm run build
```

## Notes

- Data is stored in the browser using localStorage and IndexedDB.
- Export backups regularly before making major changes.
- This project is designed to be committed to GitHub as a static frontend project.
