# PropertyRental

![Screenshot](https://raw.githubusercontent.com/elvan/property-rental-app-nextjs-react/main/_screenshots_/Screenshot%202024-02-23%20092453.png)

---

![Screenshot](https://raw.githubusercontent.com/elvan/property-rental-app-nextjs-react/main/_screenshots_/Screenshot%202024-02-23%20092518.png)

---

![Screenshot](https://raw.githubusercontent.com/elvan/property-rental-app-nextjs-react/main/_screenshots_/Screenshot%202024-02-23%20092545.png)

---

![Screenshot](https://raw.githubusercontent.com/elvan/property-rental-app-nextjs-react/main/_screenshots_/Screenshot%202024-02-23%20092756.png)

---

![Screenshot](https://raw.githubusercontent.com/elvan/property-rental-app-nextjs-react/main/_screenshots_/Screenshot%202024-02-23%20092832.png)

---

![Screenshot](https://raw.githubusercontent.com/elvan/property-rental-app-nextjs-react/main/_screenshots_/Screenshot%202024-02-23%20092849.png)

---

![Screenshot](https://raw.githubusercontent.com/elvan/property-rental-app-nextjs-react/main/_screenshots_/Screenshot%202024-02-23%20092902.png)

---

![Screenshot](https://raw.githubusercontent.com/elvan/property-rental-app-nextjs-react/main/_screenshots_/Screenshot%202024-02-23%20092918.png)

---

![Screenshot](https://raw.githubusercontent.com/elvan/property-rental-app-nextjs-react/main/_screenshots_/Screenshot%202024-02-23%20093113.png)

---

![Screenshot](https://raw.githubusercontent.com/elvan/property-rental-app-nextjs-react/main/_screenshots_/Screenshot%202024-02-23%20093157.png)

---

![Screenshot](https://raw.githubusercontent.com/elvan/property-rental-app-nextjs-react/main/_screenshots_/Screenshot%202024-02-23%20093234.png)

---

![Screenshot](https://raw.githubusercontent.com/elvan/property-rental-app-nextjs-react/main/_screenshots_/Screenshot%202024-02-23%20093252.png)

---

## Description

PropertyRental is a comprehensive real estate platform designed to bridge the gap between property owners and potential renters or buyers. This project provides a robust solution for users to explore, bookmark, and inquire about properties with ease. By integrating modern web technologies, PropertyRental enhances the property search experience with features like dynamic property listings, interactive maps, and social media sharing capabilities. The platform aims to simplify the process of finding or listing properties by offering a user-friendly interface and a set of interactive tools.

## Features

### Property Listings and Search Functionality

- **Dynamic Property Listings**: Utilizes MongoDB to fetch and display property listings dynamically, sorting them by creation date for relevance.
- **Property Search**: Implements an API route for property search with dynamic queries, allowing users to search by location and property type, enhancing the user experience with immediate feedback and loading states.

### User Authentication and Profile Management

- **User Authentication**: Integrates NextAuth with Google for user authentication, managing session states across the application.
- **Profile Management**: Provides a user-specific profile page displaying user info and property listings, with support for image uploads and cloud storage integration via Cloudinary.

### Interactive Property Details

- **Image Gallery**: Enhances property image display with PhotoSwipe, offering an interactive gallery for a better visualization of properties.
- **Map Visualization**: Incorporates Mapbox for map rendering, displaying property locations on interactive maps with pin markers.

### Messaging and Inquiries

- **Property Inquiries**: Includes a messaging feature for property inquiries, allowing logged-in users to send messages to property owners directly through the platform.
- **Message Management**: Offers functionalities to manage messages, including marking them as read/unread, deleting messages, and displaying unread message count dynamically in the Navbar.

### Additional Features

- **Bookmarking Properties**: Allows users to bookmark properties they are interested in, with real-time status checks and the ability to add or remove bookmarks.
- **Social Media Sharing**: Integrates social media share buttons for properties, enabling users to share listings on Facebook, Twitter, WhatsApp, and Email.

#### Technology Stack

- Next.js
- React
- NextAuth
- Tailwind CSS
- PhotoSwipe
- Mapbox
- MongoDB
- Cloudinary
- react-icons
- react-spinners
- react-toastify

## Installation

### Prerequisites

- Node.js and npm
- MongoDB
- Cloudinary account for image management

### Environment Setup

- Configure environment variables for MongoDB URI, Cloudinary credentials, and NextAuth secrets in a `.env.local` file.

### Installation Commands

```bash
git clone https://github.com/elvan/property-rental-app-nextjs-react.git
cd property-rental-app-nextjs-react
npm install
```

## Usage

After installation, start the development server with:

```bash
npm run dev
```

Navigate to `http://localhost:3000` to explore the properties, search for specific listings, manage bookmarks, and inquire about properties.

To view your profile and manage your listings, ensure you are logged in with your Google account via the sign-in button on the Navbar.
