# Movie Explorer Web Application

## Project Overview

This is a TypeScript-based Next.js web application for exploring and searching movies using the OMDb API. The project demonstrates modern web development practices with a focus on clean code, linting, and styling. MoviesSearch is a simple website where you can search for movies using the free OMDb database. It has a light and dark mode, a search bar in the navigation, and a home page that highlights featured movies. You can browse all movies on the movies page or see detailed information about a specific movie. It's designed to be fast and easy to use!

## ✨ Features
### Movie Exploration
- Search movies by title
- View all movies
- Detailed movie information retrieval

### 🏠 Page Overview
#### 1. Home Page
Introducing the application's purpose, the homepage provides an engaging platform for discovering a diverse selection of movies. Featuring a curated showcase of selected films, it invites users to explore and find new favorites and hidden gems, encouraging extensive movie browsing and discovery.

   ##### Key Features
   - Dynamic featured movies section
   - Responsive hero banner
   - Server-side movie fetching
   - Metadata generation for SEO
   - Theme-aware design

   ##### Component Structure
   - Hero section
   - Featured movies grid

![image](https://github.com/user-attachments/assets/689aafc2-9b5d-4fe6-b234-8937a1e92698)

#### 2. Movies Page
The Movies Page offers dynamic movie browsing and searching with seamless pagination support, integrating both server-side and client-side rendering.

   ##### Key Features
   - Dynamic movie browsing and searching
   - Pagination support
   - Server-side and client-side rendering integration
   - Metadata generation for SEO
   - Revalidation strategy (1-hour cache)

   ##### Component Structure
   - Responsive grid display of movie card with hover effects (2-5 columns based on screen size)
   - Pagination controls

![image](https://github.com/user-attachments/assets/d690d685-e3e7-4dd3-a48d-394b96dd0e04)

#### 3. Movie Detail Page
The Movie Detail Page showcases detailed information about each movie, featuring dynamic metadata generation to ensure up-to-date content. Popular movies have static paths for fast access, and daily content revalidation keeps information current and accurate.

![image](https://github.com/user-attachments/assets/78b67a95-5e88-417e-ad2f-7f716a032f1e)


### 🎨 Theme Management
- Implemented React Context for global theme state
- Dark/Light mode toggle functionality
- Responsive theme switching across components
  #### Context Management
  - ThemeContext for global state management
  - Custom useTheme hook for easy theme access
  - Default dark mode initialization

![image](https://github.com/user-attachments/assets/b9b3abe5-0076-4ce9-8060-e19ce1302262)

### Error Handling & Loading Components
   #### ⁉️ Error Handling Strategy
   - Client-side error boundary component
   - Graceful error display
   - User recovery options
      - Retry page load
      - Navigate to home page
  
![WhatsApp Image 2024-12-09 at 20 44 26_a828f9fa](https://github.com/user-attachments/assets/f83a23ca-9460-40c4-a42f-b38123794110)

   #### 🔄 Loading Experience
   - Centralized loading indicator
   - Animated spin effect
   - Full-screen coverage
   - Image blur placeholder

![WhatsApp Image 2024-12-09 at 21 40 16_cd2416e8](https://github.com/user-attachments/assets/d4ee2910-78f2-453d-9373-656940117a3a)
![WhatsApp Image 2024-12-09 at 20 53 39_ca915c26](https://github.com/user-attachments/assets/c010d6b0-1830-4955-bd9c-a38fb0df8596)

<br/> 

### Technical Highlights
- Built with Next.js (latest version)
- TypeScript for type-safe development
- TailwindCSS for responsive styling
- Axios for API interactions
- Eslint and Prettier for code quality

<br/> 

## 🛠 Project Setup
### Prerequisites
- Node.js (v18 or later)
- npm/yarn

### Installation Steps
- Clone the repository
- Install dependencies:
``` npm install ```
  
### Environment Configuration
- Create a .env.local file
- Add OMDb API credentials:

   ```NEXT_PUBLIC_OMDB_API_KEY=your_api_key```

   ```NEXT_PUBLIC_OMDB_BASE_URL=http://www.omdbapi.com/```

### 🧰 Development Scripts
- ```npm run dev```        : Start development server
- ```npm run build```      : Production build
- ```npm run lint```       : Run ESLint
- ```npm run format```     : Check code formatting
- ```npm run format:fix``` : Auto-fix formatting

## 🎨 Styling
- Custom Tailwind color palette
- Inter and Poppins fonts
- Responsive design principles

## 🔍 Code Quality
- TypeScript strict mode
- ESLint configuration
- Prettier formatting

## 📝 Learning Objectives
- Next.js framework fundamentals
- TypeScript type management
- API integration
- React Context API usage
- Theme implementation patterns
- State management
- Responsive design
- Code quality practices

## 🚧 Future Improvements
- Add user authentication
- Implement caching mechanisms
- Create more interactive UI components
- Add unit and integration tests

<br/> 
<br/> 

# 🚀 Deployment
This project is deployed using Vercel, ensuring fast and reliable hosting with automated builds on push to the main branch.
## 🌐 Live Demo
   Explore the application live here:
  👉 [Movie Explorer Web Application](https://web-intermediate-final-project.vercel.app/)
