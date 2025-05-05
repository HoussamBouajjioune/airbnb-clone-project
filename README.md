# Airbnb Clone Project

## Project Overview

This project is a full-stack clone of the popular accommodation booking platform **Airbnb**. It aims to replicate the core functionality of Airbnb, including property listings, detailed property views, booking flow, user authentication, and responsive UI/UX. This project is an excellent opportunity to practice real-world web development skills using modern technologies.

## Project Goals

- Build a fully functional booking platform
- Implement responsive, user-friendly UI
- Learn to integrate backend APIs with a frontend framework
- Practice database modeling and secure authentication
- Deploy a full-stack application to the web

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript (React)
- **Backend**: Node.js with Express or NestJS
- **Database**: PostgreSQL or MongoDB
- **Version Control**: Git and GitHub
- **UI/UX Design**: Figma
- **Deployment**: Vercel, Render, or similar platforms

## Features

- Property search and filtering
- Detailed property pages with images
- Secure user authentication (login/register)
- Booking system with checkout
- Mobile-first responsive design

---

## Repository Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/HoussamBouajjioune/airbnb-clone-project.git


## UI/UX Design Planning

### Design Goals

- Create an intuitive and seamless booking flow
- Maintain consistent visual language and layout across the app
- Ensure fast loading times for all components
- Prioritize mobile responsiveness using a mobile-first approach
- Provide accessible and inclusive design following WCAG guidelines

### Key Features

- Property search with real-time filtering
- Interactive and detailed property views
- Secure and simplified checkout process
- User authentication and profile management
- Favorites functionality for bookmarked listings

### Primary Pages

| Page Name              | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| Property Listing View  | Grid display of available properties with filters (price, location, rating) |
| Listing Detailed View  | Full details of selected property, including images, host info, and reviews |
| Simple Checkout View   | Streamlined booking and payment confirmation page                           |

### Importance of User-Friendly Design

A user-friendly design is essential for a successful booking platform. It reduces friction throughout the user journey, enhances user satisfaction, and boosts conversion rates. Clear navigation, fast-loading components, and intuitive interactions make it easier for users to find and book properties. A clean and responsive interface encourages trust and keeps users engaged, especially on mobile devices where most users browse and book accommodations.

### Color Styles

- **Primary Color**: `#FF5A5F` – used for buttons, highlights, and accents
- **Secondary Color**: `#008489` – used for secondary actions and UI elements
- **Background Color**: `#FFFFFF` – general background across the app
- **Text Color**: `#222222` – primary text color for readability
- **Secondary Text Color**: `#717171` – for less prominent information or labels

### Typography

- **Primary Font Family**: Circular
- **Font Weights**:
  - Book (400) – for secondary or supporting text
  - Medium (500) – for body text
  - Bold (700) – for headings and emphasis
- **Font Sizes**:
  - **Headings**: 24px to 32px
  - **Body Text**: 16px
  - **Secondary Text**: 14px

### Importance of Identifying Design Properties

Identifying design properties such as colors, typography, and spacing is critical when translating a Figma mockup into a live application. These properties ensure **visual consistency**, reinforce **brand identity**, and contribute to **usability and accessibility**. By adhering to predefined styles, developers and designers maintain a shared understanding, reduce guesswork, and speed up implementation while ensuring a cohesive user experience across all screens and devices.


## Project Roles and Responsibilities

Clearly defining roles within the project helps ensure smooth collaboration, accountability, and efficient development. Below are the key roles and their responsibilities in this project:

### 🧭 Project Manager
- Oversees the entire project timeline and delivery
- Coordinates between different team roles
- Ensures deliverables are met on time and within scope
- Communicates updates and blockers to stakeholders

### 💻 Frontend Developers
- Implement the user interface using React and modern CSS
- Ensure mobile-first and responsive design
- Integrate frontend components with backend APIs
- Maintain clean, modular, and reusable codebase

### 🛠️ Backend Developers
- Design and implement RESTful APIs
- Manage database models and queries
- Implement business logic, authentication, and security
- Ensure performance and scalability on the server side

### 🎨 Designers
- Create wireframes and high-fidelity mockups in Figma
- Define color palettes, typography, and layout styles
- Maintain consistency across all design components
- Ensure the design aligns with UX best practices

### 🧪 QA/Testers
- Write unit, integration, and end-to-end test cases
- Perform manual and automated testing
- Identify and report bugs or inconsistencies
- Validate new features against the design and requirements

### ⚙️ DevOps Engineers
- Set up and manage deployment environments
- Implement CI/CD pipelines for seamless integration
- Monitor performance and error logs
- Ensure infrastructure security and scalability

### 📌 Product Owner
- Defines and prioritizes features based on user needs
- Maintains the product backlog
- Represents stakeholders and ensures business value
- Validates features before release

### 🌀 Scrum Master
- Facilitates agile processes such as daily stand-ups and sprint planning
- Removes blockers and shields the team from external distractions
- Encourages continuous improvement through retrospectives
- Ensures adherence to Scrum methodology


## UI Component Patterns

In this section, we describe the key UI components that will be implemented in the AirBnB clone project. These components are designed to be reusable, ensuring consistency across the application and a smooth user experience.

### Navbar
- **Description**: The navigation bar will be the header of the application, providing quick access to key pages like the homepage, property listings, login/signup, and user profile.
- **Key Features**:
  - Logo on the left side
  - Search bar for property filtering
  - User navigation (login, account, logout)
  - Responsive menu for mobile view
  - Links to important pages (e.g., About, Contact, Help)

### Property Card
- **Description**: The property card is used to display individual properties in the property listing view. Each card will show essential information like the property's image, price, location, and ratings.
- **Key Features**:
  - Property image
  - Basic details such as price, location, and rating
  - Favorite button for users to mark their preferred properties
  - A responsive layout to adjust for various screen sizes

### Footer
- **Description**: The footer will be placed at the bottom of each page and will contain important links and information about the company, legal details, and social media.
- **Key Features**:
  - Links to pages like "Terms of Service," "Privacy Policy," and "About Us"
  - Contact information and social media links
  - Copyright information and company details

These components will be designed to be flexible and modular, ensuring they can be easily reused throughout the application and customized as needed.

