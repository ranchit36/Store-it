
# StoreIt

StoreIt is a modern storage management solution built with Next.js and Tailwind CSS. It features a clean UI, authentication, and integration with Appwrite for backend services.

## Features

- User authentication (sign up, sign in, OTP verification)
- Responsive design using Tailwind CSS
- Google Fonts integration (Poppins)
- Environment variable support for secure configuration
- Modular component structure

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ranchit36/Store-it.git
cd Store-it
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env.local` file in the root directory and add your Appwrite credentials:

```env
NEXT_PUBLIC_APPWRITE_ENDPOINT=your_appwrite_endpoint
NEXT_PUBLIC_APPWRITE_PROJECT=your_project_id
NEXT_PUBLIC_APPWRITE_DATABASE=your_database_id
NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=your_users_collection_id
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=your_files_collection_id
NEXT_PUBLIC_APPWRITE_BUCKET=your_bucket_id
NEXT_APPWRITE_KEY=your_api_key
```

### 4. Run the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

## Tech Stack

- React.js
-  CSS
- Appwrite
- JavaScript
- Nodejs
- Firebase

## License
