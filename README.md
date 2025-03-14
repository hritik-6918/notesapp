# NotesApp (React + Vite + AWS Amplify)

## Overview

NotesApp is a React-based note-taking application powered by Vite and AWS Amplify. It allows users to create, view, and delete notes with text and images. Authentication and data storage are managed using AWS Amplify services.

## Features

- User authentication with AWS Amplify
- Create, read, and delete notes
- Image upload and storage
- Real-time updates using AWS Amplify Data
- Built with React, Vite, and AWS Amplify

## Tech Stack

- **Frontend:** React, Vite
- **Backend:** AWS Amplify (Auth, Data, Storage)
- **Deployment:** AWS Amplify

## Installation

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- AWS Amplify CLI (`npm install -g @aws-amplify/cli`)

### Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/notesapp.git
   cd notesapp
   ```
2. **Install dependencies:**
   ```sh
   npm install
   ```
3. **Configure AWS Amplify:**
   ```sh
   amplify init
   amplify push
   ```
4. **Run the development server:**
   ```sh
   npm run dev
   ```

## Usage

- Open the app in your browser at `http://localhost:5173`.
- Sign in or sign up using AWS Amplify authentication.
- Create notes with a name, description, and optional image.
- View all saved notes.
- Delete unwanted notes.

## Available Scripts

| Script            | Description                  |
| ----------------- | ---------------------------- |
| `npm run dev`     | Start the development server |
| `npm run build`   | Build the production files   |
| `npm run preview` | Preview the production build |
| `npm run lint`    | Run ESLint checks            |

## AWS Amplify Backend

The backend is defined in the `amplify/` directory and includes:

- **Auth:** User authentication setup (`auth/resource.ts`)
- **Data:** Note storage and authorization (`data/resource.ts`)
- **Storage:** Image file handling (`storage/resource.ts`)

---

Developed by **curious_hritik** 🚀
