# Car Rental System
##Adminpage

![Screenshot (4)](https://github.com/user-attachments/assets/60935243-003c-4376-b1ba-d1f768985444)

![Screenshot (5)](https://github.com/user-attachments/assets/4eb6aa35-4c8c-4c64-93a4-06860691be69)

![Screenshot (6)](https://github.com/user-attachments/assets/02d73d48-a2bc-4dfc-bd3f-9dc816e33e3d)

![Screenshot (7)](https://github.com/user-attachments/assets/53751ff5-9522-430b-b357-8a01e224dc66)

![Screenshot (8)](https://github.com/user-attachments/assets/96d7dce1-341d-4c8c-bc8a-bd90564b7878)


##Homepage
![Screenshot (3)](https://github.com/user-attachments/assets/d0c96c50-9e5c-4c70-956a-39bf71c24eb2)
##Customerpage
![Screenshot (2)](https://github.com/user-attachments/assets/8995a843-7dc2-4367-9b50-6086d63f7d86)
![Screenshot (9)](https://github.com/user-attachments/assets/81a037cf-e434-492d-a9a4-f5c6bda0ccc3)

## Description
This project is a **Car Rental System** that allows users to register, log in, browse available cars, make bookings, and process payments. It includes an admin panel for managing cars, bookings, and approvals.

## Features
- **User Registration & Login**  
  Users can register and log in securely.
- **Car Rental Services**  
  Users can browse available cars and make rental bookings.
- **Payment Processing**  
  Secure payment processing for car rentals.
- **User Profile Management**  
  Users can update their profile information.
- **Booking Status Tracking**  
  Users can check the status of their bookings.
- **Admin Panel**  
  The admin can manage cars, bookings, and approvals.
- **Contact Support**  
  Users can send inquiries through a contact form.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL  

## File Structure
### User Side
- `login.html` - Login page for users  
- `login.php` - Backend login script  
- `regis.html` - User registration page  
- `register.php` - Backend registration script  
- `profile.php` - User profile management  
- `payment.php` - Payment processing page  
- `psucess.php` - Payment success confirmation page  
- `submit.php` - Form submission handling  
- `upload.php` - File upload handling  
- `Userdetails.php` - User details management  
- `booking.php` - User booking page  
- `bookinstatus.php` - User booking status tracking  
- `accres.html` - Car rental registration form  
- `cardetails.html` - Car details page (Frontend)  
- `cardetails.php` - Car details processing (Backend)  
- `contactus.php` - Contact form page  

### Admin Side
- `adminlogin.php` - Admin login page  
- `adminpage.php` - Admin dashboard  
- `addcar.php` - Add new cars to the system  
- `adminCars.php` - Manage car listings  
- `adminbook.php` - Admin view of bookings  
- `adminreturn.php` - Manage car returns  
- `approve.php` - Approve or reject rental requests  

### Database
- `carproject.sql` - Database file containing table structures and data  

### Assets
- `chip.svg` - SVG icon used in the project  

## Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/car-rental-system.git
2. Set up a local server (XAMPP, WAMP, or LAMP).
3. Place the project files in the server's htdocs folder.
4. Import the database:
     -  Open phpMyAdmin.
     -  Create a database named carproject.
     -  Import carproject.sql.
5. Start the Apache and MySQL services.
6. Open http://localhost/your-project-folder in a browser.
