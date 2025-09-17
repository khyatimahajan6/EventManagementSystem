## 🛠️ Technical Details  

### 🎨 Frontend  
- Built using **Django Templates**, **HTML**, **CSS**, and **Bootstrap 5**.  
- Fully **responsive UI**, ensuring seamless experience across desktop and mobile devices.  

### ⚙️ Backend  
- **Django** handles:
  - User authentication (Login/Signup)  
  - Event booking & management  
  - Cab booking module  
  - Role-based admin features  
- **Flask** serves as a microservice:
  - Manages and returns event data through RESTful APIs  
  - Integrated into Django using Python `requests` library  

### 🗄️ Database  
- **SQLite** used as a lightweight relational database.  
- Managed via **Django ORM** with automatic migrations for easy schema management.  

### 🔑 Authentication  
- **Role-based access control**:
  - Admins → Create, update, and delete events, view user bookings & queries  
  - Users → Book events & cabs, manage their profiles, view history  

### 🚖 Cab Booking Module  
- Capture **pickup & drop locations**, **time**, and **passenger count**.  
- View **booking history** for each user.  

### 🎫 Event Module  
- Users can **filter events by type** (Music, Education, Food, etc.).  
- Events are fetched dynamically via **Flask API** and displayed with Django templates.  

### 🖥️ Admin Dashboard  
- Simple CRUD interface for managing events.  
- View **user bookings** and **contact form submissions**.  

---

## 🧩 Problem Statement  

Traditional event management platforms have several limitations:  

- **Scattered event information** across multiple websites and apps.  
- **No integration with transport services**, making it inconvenient for users to arrange travel.  
- **Lack of real-time booking status** and updates.  
- **Separate platforms** needed for cab booking and event management.  
- **Admins struggle** with:
  - Managing events across multiple platforms  
  - Performing CRUD operations through complex interfaces  

**Our solution:**  
A **unified event management system** that integrates event browsing, booking, and cab services into a single platform. This ensures **convenience for users** and **efficient control for admins**.  

---

## 🚀 Key Features  

### 🎟️ Event Browsing & Booking  
- Browse events by **category** (Music, Education, Food, Cultural).  
- Book tickets, view booking confirmation, and track event status.  

### 🛒 Add to Cart Functionality  
- Add multiple events to the cart.  
- Seamless checkout process with a summary of selected events.  

### 🔑 Secure Sign-In / Sign-Up  
- Create accounts or log in securely.  
- Personalized user dashboard for booking history.  

### 📜 Menu & Event Display  
- Well-organized layout with **images**, **descriptions**, and **prices/ticket info**.  

### 📱 Responsive Design  
- Works across **mobile, tablet, and desktop devices**.  

### 🎁 Special Offers Page  
- Displays **current promotions and discounts** to engage users.  

### 📝 Testimonial Section  
- Showcases **user feedback** to build trust and credibility.  

### 📞 Contact & Support Information  
- Easy-to-access **contact form** for support and queries.  

### ♿ Accessibility Features  
- Designed with **inclusive navigation** for users with disabilities.  
