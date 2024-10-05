# PropertyRental

## Description

PropertyRental is a real estate application designed to streamline the process of renting, buying, and managing properties. It offers features such as property listings, user profiles, and communication tools to connect renters and landlords. The platform is built to make property discovery easy through advanced search filters, bookmarking, and property sharing. PropertyRental integrates essential tools like messaging and property management for users to interact seamlessly within a single environment.

## Features

### Featured Property Listings

- Implemented **Featured Properties** section that highlights selected properties for users to easily discover premium listings.
- Integrated **Pagination** for navigating large sets of property data, improving performance and usability.
- Enhanced **Image Gallery** with lightbox functionality using `react-photoswipe-gallery`, allowing users to view high-quality property images.

### Property Search and Filtering

- Added a **Property Search Form** enabling users to filter properties by location and type.
- Introduced dynamic **Search Results Page** to display filtered properties based on user input.
- Enhanced the homepage **Hero** section to include search capabilities directly, offering a smooth entry point for users to find relevant properties.

### Property Bookmarking, Sharing, and Contacting

- Added **Bookmark** functionality to let users save their favorite properties.
- Enabled **Social Sharing** via `ShareButtons` for platforms like Facebook, Twitter, and WhatsApp.
- Integrated a **Contact Form** on property pages, allowing users to communicate directly with property managers.
- Implemented **Property Maps** using Mapbox and Google Geocoding for displaying property locations.

### Messaging System

- Developed a **Messaging System** that includes inbox functionality, allowing users to send and receive messages related to property inquiries.
- Created actions for **adding**, **deleting**, and **marking messages as read**.
- Added **Unread Message Count** on the navbar for real-time notifications.

### Property Management

- Added **Property Management Tools** for users to add, update, and delete their property listings.
- Created a **Profile Page** where users can view and manage their listed properties.
- Integrated **Edit and Delete** functionality with forms for editing property details and deleting listings, with real-time feedback using `react-toastify`.

### User Authentication and Profiles

- Implemented **Google Authentication** using NextAuth, allowing users to securely sign in and manage their profiles.
- Created user-specific routes like `/profile` and `/properties/add` protected by authentication middleware.

### Responsive UI and Loading Indicators

- Designed a responsive **Navbar** with login and menu options, providing an optimized experience across devices.
- Added loading spinners and a custom 404 page for enhanced user experience during data fetches and routing errors.

#### Technology Stack

- **Frontend**: Next.js, React, Tailwind CSS
- **Backend**: Node.js, MongoDB (Mongoose)
- **Authentication**: NextAuth with Google Provider
- **File Storage**: Cloudinary for image uploads
- **Map Services**: Mapbox and Google Geocoding for location display
- **State Management**: React Context API (Global Context)
- **Other Libraries**: React Icons, React Toastify, Photoswipe for image galleries

## Installation

### Prerequisites

- **Node.js** (v14 or above)
- **MongoDB** (running locally or a MongoDB Atlas account)
- **Google Cloud** project for authentication and geocoding
- **Cloudinary** account for image uploads

### Environment Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/elvan/property-rental-app-nextjs-react.git
   cd property-rental-app-nextjs-react
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables. Create a `.env.local` file in the root of your project with the following values:

   ```env
   MONGODB_URI=<your-mongodb-connection-string>
   NEXTAUTH_SECRET=<your-next-auth-secret>
   NEXTAUTH_URL=http://localhost:3000
   GOOGLE_CLIENT_ID=<your-google-client-id>
   GOOGLE_CLIENT_SECRET=<your-google-client-secret>
   NEXT_PUBLIC_MAPBOX_TOKEN=<your-mapbox-token>
   NEXT_PUBLIC_GOOGLE_GEOCODING_API_KEY=<your-google-geocoding-api-key>
   CLOUDINARY_URL=<your-cloudinary-url>
   ```

4. Run the development server:

   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

## Usage

### Property Search

1. Use the **Property Search Form** on the homepage or the properties page to filter properties by location and type.
2. Browse the search results or navigate the featured properties section for recommended listings.

### Bookmarking Properties

1. To save a property, click the **Bookmark** button on the property details page.
2. View your bookmarked properties under the **Saved Properties** section.

### Messaging

1. Users can contact property managers directly by filling out the **Contact Form** on a property's details page.
2. View incoming messages in the **Messages** section, where you can read, delete, or mark messages as read.

### Managing Properties

1. Log in using your Google account to access your **Profile**.
2. Add new properties, or edit and delete existing listings from your **Profile Page**.
3. Use the **Property Management Tools** to modify property details, images, and availability.
