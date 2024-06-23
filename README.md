# Voom | A Minimalistic Zoom Clone

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

![Screenshot 2024-06-23 at 11 26 04 PM](https://github.com/themihirmathur/Voom/assets/92594107/0c9081c5-a9eb-416d-ad1d-2978648ee4ca)

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Introduction
Voom is a streamlined, modern video conferencing tool inspired by the widely used Zoom platform. Built with the latest technologies, Voom offers a secure and intuitive experience for users to log in, create meetings, and utilize a variety of conferencing features. Our platform supports essential functionalities such as recording, screen sharing, and participant management, all wrapped in a minimalistic design.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## ⚙️ Tech Stack
- **Next.js**: A powerful React framework for building server-side rendered applications.
- **TypeScript**: A strongly typed programming language that builds on JavaScript, adding static type definitions.
- **Clerk**: A user authentication and management solution that simplifies secure login and authorization.
- **getstream**: A scalable, feature-rich activity feed and chat API for enhancing user interaction.
- **shadcn**: A component library for creating beautiful and consistent UI.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Features

### Authentication
- **Secure Login**: Implemented via Clerk, supporting social sign-on and traditional email/password methods.
- **Authorization**: Ensures appropriate access levels and permissions within the platform.

### Meeting Management
- **New Meeting**: Quickly start a new meeting, configuring camera and microphone settings beforehand.
- **Meeting Controls**: Full participant control, including:
  - Recording sessions
  - Emoji reactions
  - Screen sharing
  - Mute/unmute options
  - Sound adjustments
  - Grid layout
  - Participant list view
  - Individual participant management (pinning, muting, unmuting, blocking, allowing video share)
- **Exit Meeting**: Options to leave a meeting or end it for all attendees.

### Scheduling & History
- **Schedule Future Meetings**: Input details (date, time) to schedule and manage future meetings.
- **Past Meetings List**: Access a list of previous meetings with details and metadata.
- **View Recorded Meetings**: Review or reference recordings of past meetings.

### Personal Room
- **Unique Meeting Link**: Each user has a personal room with a unique link for instant meetings.

### Join Meetings
- **Via Link**: Easily join meetings created by others by providing a meeting link.

### Real-time Interaction
- **Secure Real-time Functionality**: Ensures all interactions within the platform are secure and occur in real-time, maintaining user privacy and data integrity.

### Responsive Design
- **Adaptive UI**: Designed to provide an optimal user experience across devices, adapting seamlessly to different screen sizes and resolutions.

### Additional Features
- **Code Architecture**: Emphasizes clean, maintainable, and reusable code.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## 🤸 Quick Start

You can follow these steps to set up the project locally on your machine.

### Prerequisites

Ensure you have the following installed on your machine:
- Git
- Node.js
- npm (Node Package Manager)

### Cloning the Repository

```sh
git clone https://github.com/adrianhajdin/zoom-clone.git
cd zoom-clone
```

### Installation

Install the project dependencies using npm:

```sh
npm install
```

### Set Up Environment Variables

Create a new file named `.env` in the root of your project and add the following content:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

Replace the placeholder values with your actual Clerk and getstream credentials. Obtain these credentials by signing up on the [Clerk website](https://clerk.dev) and [getstream website](https://getstream.io).

### Running the Project

```sh
npm run dev
```

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

---

By following these steps, you'll have Voom up and running on your local machine, ready to provide a seamless and feature-rich video conferencing experience.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>
