# Decentralized Exchange (DEX) using 0x API

This project is a decentralized exchange (DEX) built using the 0x API for fetching swap quotes and executing trades. It consists of a React-based frontend and a Node.js/Express backend.

## Frontend (React)

The frontend is built using React, TypeScript, and Vite. It utilizes the following libraries:

-   **@rainbow-me/rainbowkit:** For wallet connection.
-   **@tanstack/react-query:** For data fetching and caching.
-   **axios:** For making HTTP requests.
-   **ethers/viem/wagmi:** For interacting with the Ethereum blockchain.
-   **lucide-react:** For icons.
-   **qs:** For query string parsing.
-   **tailwindcss:** For styling.

### Installation

1.  Navigate to the `frontend` directory:

    ```bash
    cd frontend
    ```

2.  Install dependencies:

    ```bash
    npm install
    ```

3.  Start the development server:

    ```bash
    npm run dev
    ```

### Build

To build the frontend for production:

```bash
npm run build
```

### Backend (Node.js/Express)
The backend is built using Node.js, TypeScript, and Express. It acts as a proxy for the 0x API, handling requests from the frontend.

1.  Navigate to the `backend` directory:

    ```bash
    cd backend
    ```

2. Install dependencies:

   ```bash
   npm install
   ```

3.  Start the development server:

   ```bash
  npm run dev
  ```

###0x API Key
Important: You need to add your 0x API key to the backend/src/index.ts file.
