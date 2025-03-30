# Wanderlux - AI-Powered Hotel Booking Platform

Wanderlux is a modern hotel booking platform that leverages AI to provide personalized hotel recommendations and an enhanced booking experience. The application features a clean, intuitive interface with step-by-step search capabilities, comprehensive hotel listings, and a seamless booking flow.

<img width="1422" alt="homepage" src="https://github.com/user-attachments/assets/dbe65c9a-f32b-447b-9b5b-7e9aff64617f" />


## Repository Structure

Attached is the public repository links of front end and backend:

- **[https://github.com/nasma321/horizone]**: React-based user interface => https://aidf-horizone-frontend-nasma.netlify.app/
- **[https://github.com/nasma321/horizone-backend]**: Express and Node.js API server => https://aidf-horizone-backend-nasma.onrender.com/

## Features Implemented

### Core Features

#### 1. UI and UX Overhaul
The application received a complete redesign with a modern, clean interface focused on user experience:

- **Step-by-Step Search Form**: Replaced the single input search with an intuitive multi-step form
  
  <img width="681" alt="image" src="https://github.com/user-attachments/assets/5dd6bda3-cc8d-4f68-a50d-9503a231c14c" />
<img width="681" alt="image" src="https://github.com/user-attachments/assets/010641a0-6b1d-4e77-9e76-965f8cbb1680" />
<img width="681" alt="image" src="https://github.com/user-attachments/assets/b5a5c900-6251-4a18-968a-85806b2e3612" />
<img width="681" alt="image" src="https://github.com/user-attachments/assets/744af88b-7470-43a2-8618-07d1317840a1" />
<img width="681" alt="image" src="https://github.com/user-attachments/assets/69253d3a-5ab4-4b3a-93f3-794ed013922f" />

  
- **Enhanced Visual Design**: Implemented a consistent color scheme, typography, and visual elements
- **Responsive Layout**: Fully responsive design that works on mobile, tablet, and desktop devices
- **Animated Transitions**: Smooth animations and transitions for a polished user experience

#### 2. Hotels Page with Server-Side Filtering and Sorting

<img width="1456" alt="image" src="https://github.com/user-attachments/assets/d7c2ad4b-19bb-43c0-81d7-501a87ed154f" />

- **Location Filtering**: Filter hotels by location via server-side API
- **Price Sorting**: Sort hotels by price (ascending or descending) using server-side logic
- **Combined Filtering and Sorting**: Both filtering and sorting can be used simultaneously
- **Optimized Performance**: All filtering and sorting logic implemented on the server for better performance

#### 3. Enhanced Hotel Details Page

<img width="1456" alt="image" src="https://github.com/user-attachments/assets/26ed9b88-d0fb-450e-8561-1a0efa7455d1" />

<img width="1456" alt="image" src="https://github.com/user-attachments/assets/9149dcc2-976c-46a7-9e77-0cf0832c49f6" />


- **Comprehensive Information Display**: Detailed hotel information including amenities, policies, and room types
- **Room Type Selection**: Display of available room types with pricing and features
- **Image Gallery**: Multiple hotel images with gallery view
- **Booking Interface**: Direct booking capability from the hotel details page

<img width="1456" alt="image" src="https://github.com/user-attachments/assets/7dc45689-36b4-49e5-8dcc-981a2f3c36f3" />


#### 4. User Bookings Management

- **Booking History**: View all past and upcoming bookings
- **Booking Details**: Comprehensive booking information display
- **Cancellation Capability**: Users can cancel bookings when applicable
- **Payment Status Tracking**: Visual indicators for payment status (paid, pending, refunded)

<img width="1456" alt="image" src="https://github.com/user-attachments/assets/c65a0d1f-33ce-4975-9ae3-9873a9572251" />

<img width="1456" alt="image" src="https://github.com/user-attachments/assets/54c6edc5-ae7d-443d-b529-f905dc703705" />

<img width="1456" alt="image" src="https://github.com/user-attachments/assets/09aab16e-a9d1-4033-937d-9b5a2fa19a0f" />



### Additional Features

#### 1. Enhanced Hotel Creation for Admins

<img width="1456" alt="image" src="https://github.com/user-attachments/assets/5cad58c9-98b4-45b0-837e-84fac55edf74" />
<img width="1456" alt="image" src="https://github.com/user-attachments/assets/55d96438-3ed9-4c77-80bf-1b9622ae7e72" />
<img width="1456" alt="image" src="https://github.com/user-attachments/assets/fda44dcf-78eb-44e6-9ef8-0093194bd80c" />
<img width="1456" alt="image" src="https://github.com/user-attachments/assets/5a0ff8af-7d72-40a3-9f77-b8952ef288b9" />


- **Amenities Management**: Add and manage hotel amenities
- **Room Type Configuration**: Create different room types with varying prices
- **Automated Room Generation**: System automatically generates rooms based on configured types
- **Policy Settings**: Define check-in/out times and cancellation policies

#### 2. Advanced Booking System

<img width="1456" alt="image" src="https://github.com/user-attachments/assets/5411aeed-211c-46db-aa5a-52531e0c26bd" />


- **Room Type Selection**: Users can select specific room types when booking
- **Automatic Room Assignment**: System automatically assigns an available room of the selected type
- **Special Requests**: Users can include special requests with their booking
- **Price Calculation**: Dynamic price calculation based on room type and stay duration


## Technology Stack

### Frontend
- React
- Redux Toolkit for state management
- Tailwind CSS for styling
- Framer Motion for animations
- React Router for navigation
- Clerk for authentication

### Backend
- Node.js and Express
- MongoDB with Mongoose
- LangChain for AI processing
- OpenAI integration
- JWT authentication with Clerk


> **Note**: Admin access is required for certain features like hotel creation. Please reach out to me if you need admin account credentials for testing these features.
