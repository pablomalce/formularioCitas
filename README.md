# formularioCitas

A small React app for booking and managing veterinary appointments, built as a learning exercise.

## Context

Built in August 2020 (three commits, 26–27 Aug 2020) while I was learning React. It is a course exercise: a single-page "patient administrator" for a vet clinic. The UI text is in Spanish.

## What it does

- A form to create an appointment: pet name, owner name, date, time and symptoms.
- Validates that every field is filled in and shows an error message if one is missing.
- Gives each appointment an id with `uuid` and lists them next to the form, with a button to delete each one.
- Tries to save the list to `localStorage`. This is incomplete: the initial state is always an empty array, so saved appointments are not loaded back after a page reload.

## Stack

- React 16 with function components and hooks (`useState`, `useEffect`), PropTypes
- Create React App (`react-scripts` 3.4)
- Skeleton CSS and Normalize.css from a CDN

Main files: `src/App.js`, `src/components/Formulario.js` (the form) and `src/components/Cita.js` (one appointment card). There are no tests.

## Running it

```bash
npm install
npm start   # http://localhost:3000
```

These are the standard Create React App scripts from `package.json`. The 2020 dependencies may need updating to run on a current Node version.

## Status

Archived learning project from 2020. Not maintained.
