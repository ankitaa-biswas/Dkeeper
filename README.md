# DKeeper App

DKeeper is a simple note-keeping application built with **React** for the frontend and **Motoko (DFINITY's Internet Computer)** for the backend. Users can create, read, and delete notes, which are stored on the blockchain.

## Features
- Add new notes with a title and content.
- View all stored notes.
- Delete notes from the list.
- Data persistence using DFINITY's Internet Computer.

## Tech Stack
- **Frontend**: React, JavaScript, HTML, CSS
- **Backend**: Motoko (DFINITY Smart Contracts)
- **Deployment**: DFINITY Canister (ICP Blockchain)

## Installation & Setup

### Prerequisites
Ensure you have the following installed:
- **Node.js** and **npm** (for frontend development)
- **DFX SDK** (for Internet Computer development)
- **Git** (for version control)

### Clone the Repository
```sh
git clone https://github.com/ankitaa-biswas/Dkeeper.git
cd Dkeeper
```

### Install Dependencies
#### 1. Install frontend dependencies:
```sh
cd src/dkeeper_frontend
npm install
```

#### 2. Install DFINITY SDK (if not installed):
```sh
sh -ci "$(curl -fsSL https://internetcomputer.org/install.sh)"
```

### Start the Local Development Server
#### 1. Start the DFINITY local network:
```sh
dfx start --background
```

#### 2. Deploy the backend smart contract:
```sh
dfx deploy
```

#### 3. Start the frontend:
```sh
npm start
```
This will launch the application at `http://localhost:3000/`.


