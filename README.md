# VirtuMeet

## Description

VirtuMeet is a video calling application built for teams. It provides a workspace for video meetings, powered by Stream and Clerk.

## Key Features

  * **Video Calling**: Instantly start or schedule meetings.
  * **Authentication**: Secure user authentication is handled by Clerk.
  * **Meeting Management**: Users can view upcoming and previous calls, as well as meeting recordings.
  * **Personal Room**: Each user has a personal meeting room with a unique invite link.

## Technology Stack

  * **Framework**: Next.js
  * **Authentication**: Clerk
  * **Video SDK**: Stream Video
  * **Language**: TypeScript
  * **Styling**: Tailwind CSS
  * **UI Components**: Shadcn UI

## Getting Started

### Prerequisites

You need to have the following installed on your machine:

  * Node.js (\>= 18.17.0)
  * npm or Yarn

### Installation

1.  Clone the repository:
    ```
    git clone https://github.com/Sakshamk022/VirtuMeet.git
    ```
2.  Navigate to the project directory:
    ```
    cd virtumeet
    ```
3.  Install the dependencies:
    ```
    npm install
    ```

### Running the Application

  * To run the application in development mode:
    ```
    npm run dev
    ```
  * To build the application for production:
    ```
    npm run build
    ```
  * To start the built application:
    ```
    npm run start
    ```

### Environment Variables

You will need to set up the following environment variables. Create a `.env.local` file in the root directory and add the following keys:

  * `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY`
  * `CLERK_SECRET_KEY`
  * `NEXT_PUBLIC_STREAM_API_KEY`
  * `STREAM_SECRET_KEY`
  * `NEXT_PUBLIC_BASE_URL`

The application uses these keys for Clerk authentication and Stream Video functionality.
