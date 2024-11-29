# 🍔 CampusEats - Food Ordering Website 🍕

**CampusEats** is a food ordering website designed for college campuses, allowing students to browse menus, add items to their cart, and place orders seamlessly. The project features secure authentication, order history tracking, and an admin panel to manage the menu and orders. This website is built with modern web technologies to provide a fast and user-friendly experience for both students and administrators.

---

## 🚀 Features
- **Secure Authentication**: User login and registration via **Google Authentication** and **Next-Auth**.
- **Order Management**: Students can browse a menu, add items to their cart, and place orders.
- **Order History**: Users can view their order history and track order status.
- **Admin Panel**: Admins can manage the menu, view all orders, and update order statuses.
- **Responsive Design**: Fully responsive design to support both desktop and mobile views.

---

## 💻 Tech Stack

### **Frontend:**
- **Next.js**: React-based framework for server-side rendering and static site generation.
- **React**: For building reusable components and managing the UI.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI design.

### **Backend:**
- **MongoDB**: NoSQL database to store user information, orders, and menu data.
- **Next-Auth**: For secure authentication using third-party services like Google.

### **Other Tools:**
- **GitHub**: For version control and collaboration.

---

## 📦 Setup & Installation

To run the project locally, follow these steps:

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/CampusEats.git
cd CampusEats
```

## 📦 Setup & Installation

### 2. Install Dependencies
Make sure you have **Node.js** and **npm** installed. Then, install the required dependencies by running:

```bash
npm install
```
### 3. Set Up Environment Variables
Create a `.env.local` file in the root of the project and add your environment variables for Google authentication:

```bash
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_nextauth_secret
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
MONGODB_URI=your_mongo_database_uri
```

## 📝 Usage

### For Students:
- **Login**: Use **Google Authentication** to sign in.
- **Browse Menu**: View available food items categorized by type (e.g., Snacks, Drinks, etc.).
- **Add to Cart**: Add items to your cart, view the total cost, and proceed to checkout.
- **Track Orders**: Check your order status and view your order history.

### For Admins:
- **Login**: Use **Google Authentication** to sign in as an admin.
- **Manage Menu**: Add or remove items from the menu.
- **View Orders**: View all orders placed by students, update their status (e.g., Pending, Completed).

---

## 🛠️ Code Explanation

The app is built with the following architecture:

- **Authentication**: The **Next-Auth** module handles user authentication via Google, storing user sessions in a secure cookie.
- **Database**: **MongoDB** stores data for users, orders, and the menu. The app uses **Mongoose** to interact with the database.
- **Pages**:
  - **Home Page**: Displays the menu and provides options for login or registration.
  - **User Dashboard**: Shows the cart, order history, and the option to place new orders.
  - **Admin Panel**: Allows the admin to manage the menu and view all orders.
- **UI**: The UI is built using **React** components, with **Tailwind CSS** for styling.

---

<!--## 📈 Output Example

- **Menu Page**: Displays food items in a categorized list with images, descriptions, and prices.
- **Cart Page**: Shows the items in the cart with a checkout option.
- **Admin Panel**: Allows the admin to manage the menu and view order details.

---
-->
## 🔗 Links

- **Google Authentication Setup**: [Google Developer Console](https://console.developers.google.com/)
- **MongoDB Setup**: [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)

---

## 🚧 Limitations

- **Menu Customization**: Admins can add or remove items, but menu updates are not real-time.
- **Payment Gateway**: Currently, the app doesn’t integrate with any payment system (future feature).

