# MVP


 Architecture:

Frontend:
- HTML, CSS, JavaScript for the user interface.
- React.js or Vue.js for a responsive and interactive user experience.
- Axios or Fetch for API communication.

Backend:
- Node.js or Django for server-side development.
- Express.js or Django REST Framework for creating API routes.
- MongoDB or PostgreSQL for database storage.


Minimum Viable Product (MVP) 
1. Homepage:
   - Welcome message and a brief introduction to your dealership.
   - Featured cars with images, prices, and key details.
   - Search bar for users to quickly find specific makes, models, or price ranges.

2. Car Listings:
   - A page with a comprehensive list of available cars.
   - Filter options (e.g., brand, model, year, price range).
   - Each listing includes a thumbnail image, basic details, and a link to view more information.

3. Car Details Page:
   - Detailed information about a specific car, including specifications, features, and pricing.
   - High-quality images of the car from different angles.
   - Contact form or button for inquiries about the car.

4. User Registration and Login:
   - Allow users to create accounts to save favorite cars and receive updates.
   - Social media login options for ease of access.

5. Contact Information:
   - A dedicated page with dealership contact information.
   - Contact form for general inquiries.
   - Google Maps integration for the dealership location.

6. Responsive Design:
   - Ensure the website is mobile-friendly to cater to users on various devices.

7. Admin Panel:
   - Backend admin panel to manage car listings, user accounts, and inquiries.
   - Basic analytics to track website traffic and user behavior.

8. Search Engine Optimization (SEO):
   - Implement basic SEO practices to enhance the website's visibility on search engines.

9. Newsletter Signup:
   - Allow users to subscribe to newsletters for updates on new arrivals, promotions, or dealership news.

10. Social Media Integration:
    - Links to your dealership's social media profiles.
    - Share buttons on car listings.

11. Terms and Conditions/Privacy Policy:
    - Create and display clear terms of service and privacy policy.





API Routes:
1. Car Listings:
   - `GET /api/cars`: Retrieve a list of all cars.
   - `GET /api/cars/:id`: Retrieve details of a specific car.

2. User Management:
   - `POST /api/users/register`: Register a new user.
   - `POST /api/users/login`: Authenticate a user.
   - `GET /api/users/profile`: Retrieve user profile information.

3. Inquiries:
   - `POST /api/inquiries`: Submit an inquiry about a specific car.
   - `GET /api/inquiries`: Retrieve a list of user inquiries.
   - `PUT /api/inquiries/:id`: Update the status of an inquiry.



 Data Modeling:

**User:**
- `id`
- `username`
- `email`
- `password` (hashed)
- `created_at`

**Car:**
- `id`
- `make`
- `model`
- `year`
- `price`
- `description`
- `image_urls`
- `created_at`

**Inquiry:**
- `id`
- `user_id` (foreign key)
- `car_id` (foreign key)
- `message`
- `status` (e.g., 'pending', 'resolved')
- `created_at`

User Story:

"As a car buyer, I want to be able to browse the available cars on the dealership website, view detailed information about a specific car, and easily inquire about a car that interests me. Additionally, I want the ability to register an account to save my favorite cars and receive updates about new arrivals and promotions."

 Mockup:


Progress:

I will rate the progress made so far on a scale of 1 - 10 , 7.
The homepage, Car listing page, the contact page and the Responsive design have been completed for the project so far .
Admin panel , the sign page has not been completed.
