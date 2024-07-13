# VideoConf App

VideoConf is a robust video conferencing application that enables users to create, plan, record, and join meetings effortlessly. Built with modern web technologies, the app ensures seamless video conferencing and efficient meeting management.

## Features

- **Create Meetings**: Schedule new meetings with customizable settings.
- **Plan Meetings**: Organize upcoming meetings efficiently.
- **Record Meetings**: Record meetings for future reference.
- **Join Meetings**: Join scheduled meetings with a single click.
- **Authentication**: Secure authentication using NEXT.js with TypeScript.
- **User Interface**: Beautiful and responsive UI using shadcn/ui.

## Tech Stack

- **Frontend**: NEXT.js with TypeScript
- **UI Library**: shadcn/ui
- **Authentication**: Clerk
- **API**: RESTful API using NEXT.js API routes
- **Video Conferencing**: Stream
- **Backend**: Node.js

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn
- Clerk account for authentication

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/asmit27rai/VideoConfa.git
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up environment variables:

    Create a `.env.local` file in the root directory and add your environment variables:

    ```.env.local
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
    CLERK_SECRET_KEY=

    NEXT_PUBLIC_CLERK_SIGN_IN_URL = /sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL = /sign-up

    NEXT_PUBLIC_STREAM_API_KEY = 
    STREAM_SECRET_KEY=

    NEXT_PUBLIC_BASE_URL=localhost:3000

    ```

4. Start the development server:

    ```bash
    npm run dev
    ```

    The app should be running at [http://localhost:3000](http://localhost:3000).

## Usage

### Creating a Meeting

1. Log in using your credentials.
2. Navigate to the "Create Meeting" page.
3. Fill in the meeting details and save.

### Planning a Meeting

1. Go to the "Plan Meeting" section.
2. View and organize your upcoming meetings.

### Joining a Meeting

1. Go to the "Join Meeting" page.
2. Enter the meeting ID or join from your dashboard.

### Recording a Meeting

1. Start a meeting.
2. Click on the "Record" button to start recording.
3. Save the recording for future reference.

## Acknowledgments

This project was developed following the tutorial from the [JS Mastery](https://www.youtube.com/c/JavaScriptMastery) channel. Special thanks to the JS Mastery team for their excellent tutorials and guidance.

