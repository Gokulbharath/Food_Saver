# Food Saver App  

## Overview  
The **Food Saver App** is a platform designed to reduce food wastage and connect donors with organizations or individuals in need. It allows users to donate excess food, groceries, or surplus stock while also enabling buyers to purchase groceries at reduced prices. The app uses **React** and **Vite** for a seamless and modern user experience, with **Firebase** for backend support like authentication and database management.

---

## Features  
- **User Authentication**: Secure login and signup for donors, buyers, and NGOs using Firebase Authentication.  
- **Real-time Food Donation Alerts**: Instant notifications for available food donations.  
- **Food Expiry Prediction**: Smart alerts to predict and track food expiration based on donation data.  
- **Donation Calendar**: Organize and schedule donations efficiently.  
- **Map Integration**: Navigate to donation or pickup locations using integrated maps.  
- **Interactive Forum**: Share and view food details such as condition, expiry date, quantity, and photos.  
- **Simple and Responsive Design**: Ensures usability across all devices.  

---

## Tech Stack  
### Frontend:  
- **React**: Component-based UI development.  
- **Vite**: Fast and efficient development environment.  

### Backend:  
- **Firebase**:  
  - **Authentication**: For secure user login and registration.  
  - **Firestore**: Real-time database for storing user data and food donations.  

---

## Installation  

### Prerequisites  
- Node.js installed on your system.  
- Firebase account for configuring the backend.  

### Steps to Setup  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/food-saver-app.git  
   ```  

2. Navigate to the project directory:  
   ```bash  
   cd food-saver-app  
   ```  

3. Install dependencies:  
   ```bash  
   npm install  
   ```  

4. Configure Firebase:  
   - Go to the Firebase Console and create a new project.  
   - Enable **Authentication** and set up your desired sign-in methods.  
   - Create a Firestore database.  
   - Copy your Firebase configuration and replace the placeholders in your project’s environment file.  

5. Start the development server:  
   ```bash  
   npm run dev  
   ```  

6. Open the app in your browser:  
   ```  
   http://localhost:5173  
   ```  

---

## Usage  

### Donors:  
- Register or log in to your account.  
- Add food donation details, including photos, expiry date, and quantity.  
- Track your donations and receive notifications for pickups.  

### Buyers/NGOs:  
- Browse available donations or discounted groceries.  
- Navigate to pickup locations using the map feature.  
- Organize and schedule donations using the calendar.  

---

## Screenshot  
*(Add screenshots of the app interface showcasing key features like donation form, calendar, or map integration.)*  

---

## Future Enhancements  
- Advanced analytics for tracking food donations and impact.  
- Multi-language support.  
- Chatbot for easier interaction between users.  

---

## License  
This project is licensed under the [MIT License](LICENSE).  

---

## Contributing  
Contributions are welcome! Please fork the repository, make changes, and submit a pull request.  

---

Feel free to adjust the content further to reflect any additional features or customizations you've implemented!
