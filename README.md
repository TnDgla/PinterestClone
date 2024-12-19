---

## **Project Name: Product Store Web App**

The **Product Store Web App** is a full-stack MERN application that allows users to browse, search, and purchase products. The app features user authentication, product management, and a shopping cart, providing an interactive platform for managing e-commerce functionality.

---

## **Mission and Objectives**

### **Mission:**
To create an efficient, scalable, and user-friendly e-commerce platform while providing developers with hands-on experience in full-stack development using modern web technologies.

### **Objectives:**
1. **Product Management:**
   - Display products with details like name, price, and description.
   - Enable CRUD operations for admin users.

2. **User Authentication:**
   - Implement secure user login and registration.
   - Support role-based access for admin and regular users.

3. **Shopping Cart and Checkout:**
   - Allow users to add, remove, and update products in their cart.
   - Integrate a payment gateway for seamless transactions.

4. **Search and Filters:**
   - Enable users to search for products and apply filters by category and price.

5. **Responsive Design:**
   - Optimize the app for desktop and mobile devices.

6. **Deployment:**
   - Host the app on a scalable platform for public accessibility.

---

## **Technology Stack**

### **Frontend:**
1. **React.js**
   - **Why?** Simplifies UI development with reusable components.
   - **Use Case:** Handles product display, user interactions, and navigation.

2. **Redux**
   - **Why?** Manages application state effectively.
   - **Use Case:** Synchronizes user actions like adding to cart across components.

3. **Bootstrap**
   - **Why?** Provides pre-designed, responsive UI components.
   - **Use Case:** Styles forms, buttons, and product cards.

### **Backend:**
1. **Node.js**
   - **Why?** Handles server-side logic and API requests.
   - **Use Case:** Manages authentication, product data, and orders.

2. **Express.js**
   - **Why?** A minimal web framework for building RESTful APIs.
   - **Use Case:** Handles routing and middleware.

3. **JWT (JSON Web Tokens):**
   - **Why?** Ensures secure user authentication.
   - **Use Case:** Manages user sessions.

4. **Bcrypt.js:**
   - **Why?** Encrypts passwords for secure storage.
   - **Use Case:** Safeguards user credentials.

### **Database:**
1. **MongoDB**
   - **Why?** A NoSQL database for flexible schema design.
   - **Use Case:** Stores product details, user profiles, and order data.

2. **Mongoose**
   - **Why?** Provides a schema-based solution for MongoDB.
   - **Use Case:** Manages database models and queries.

### **Payment Gateway:**
1. **Stripe**
   - **Why?** Simplifies payment integration.
   - **Use Case:** Handles secure payment transactions.

---

## **Workflow Overview**
The application workflow involves users browsing products, adding them to the cart, and proceeding to checkout. Admin users can manage the product inventory, and all transactions are securely processed through the Stripe payment gateway.

### **FlowChart**

![image](https://github.com/user-attachments/assets/5a7f76c0-7e4e-4a3d-8109-7baf39c1ec7c)

---

### **Project Structure for Feature Implementation**
This project is structured to ensure a systematic and incremental development process. Each week builds upon the previous deliverables, enabling a smooth transition from basic to advanced functionalities.

**NOTE:** Participants are encouraged to customize the design and functionality to make the application unique.

---

## **Week-by-Week Implementation Plan**

### **Week 1: Project Setup and Backend Initialization**
- **Goal:** Set up the foundational structure and backend for the Product Store.
- **Tasks:**
  1. Install Node.js and initialize the project.
     - **Reading:** [Node.js Docs](https://nodejs.dev/learn)
     - **Video:** [Node.js Setup](https://www.youtube.com/watch?v=TlB_eWDSMt4)
  2. Set up Express.js and configure basic routes.
     - **Reading:** [Express.js Docs](https://expressjs.com/)
     - **Video:** [Express.js Crash Course](https://www.youtube.com/watch?v=L72fhGm1tfE)
  3. Install and configure MongoDB for the database.
     - **Reading:** [MongoDB Docs](https://www.mongodb.com/docs/manual/)
     - **Video:** [MongoDB Tutorial](https://www.youtube.com/watch?v=fgTGADljAeg)
  4. Set up environment variables using dotenv.
     - **Reading:** [dotenv Package](https://www.npmjs.com/package/dotenv)
     - **Video:** [Environment Variables Guide](https://www.youtube.com/watch?v=17UVejOw3zA)

- **Deliverables:**
  - Backend server with MongoDB connection and basic API routes.

---

### **Week 2: User Authentication**
- **Goal:** Implement user registration and login with role-based access.
- **Tasks:**
  1. Create user schema with Mongoose.
     - **Reading:** [Mongoose Guide](https://mongoosejs.com/docs/guide.html)
     - **Video:** [Mongoose Models Tutorial](https://www.youtube.com/watch?v=DZBGEVgL2eE)
  2. Set up JWT-based authentication.
     - **Reading:** [JWT Basics](https://jwt.io/introduction/)
     - **Video:** [JWT Implementation](https://www.youtube.com/watch?v=mbsmsi7l3r4)
  3. Build login and signup APIs.
     - **Reading:** [RESTful API Design](https://restfulapi.net/)
     - **Video:** [Building APIs](https://www.youtube.com/watch?v=pKd0Rpw7O48)

- **Deliverables:**
  - Secure authentication system with role-based access control.

---

### **Week 3: Product Management**
- **Goal:** Allow admin users to manage the product inventory.
- **Tasks:**
  1. Design the product schema in MongoDB.
     - **Reading:** [MongoDB Schema Design](https://www.mongodb.com/docs/manual/data-modeling/)
     - **Video:** [Designing Schemas](https://www.youtube.com/watch?v=3yqDxhR2XxE)
  2. Create APIs for CRUD operations on products.
     - **Reading:** [Express CRUD Guide](https://expressjs.com/en/starter/basic-routing.html)
     - **Video:** [CRUD Operations](https://www.youtube.com/watch?v=3xRMUDC74Cw)

- **Deliverables:**
  - Functional product management APIs.

---

### **Week 4: Shopping Cart and Checkout**
- **Goal:** Enable users to add products to their cart and proceed to checkout.
- **Tasks:**
  1. Implement cart functionality in the frontend.
     - **Reading:** [React State Management](https://react.dev/learn)
     - **Video:** [React State Management Guide](https://www.youtube.com/watch?v=35lXWvCuM8o)
  2. Integrate Stripe for payment processing.
     - **Reading:** [Stripe Docs](https://stripe.com/docs)
     - **Video:** [Stripe Integration](https://www.youtube.com/watch?v=volAze3fpt0)

- **Deliverables:**
  - Functional shopping cart and payment integration.

---

### **Week 5: Search and Filters**
- **Goal:** Add search and filter functionality to enhance user experience.
- **Tasks:**
  1. Implement search by product name or category.
     - **Reading:** [React Search Implementation](https://react.dev/reference/react-dom/components/form)
     - **Video:** [Building Search Features](https://www.youtube.com/watch?v=Objl-IGpM98)
  2. Add filters for price range and categories.
     - **Reading:** [React Filter Components](https://reactjs.org/docs/components-and-props.html)
     - **Video:** [Filter Implementation](https://www.youtube.com/watch?v=CwAr9cUJA6A)

- **Deliverables:**
  - Enhanced product browsing experience with search and filters.

---

### **Week 6: Testing and Deployment**
- **Goal:** Test the application and deploy it to a live environment.
- **Tasks:**
  1. Write unit tests for components and APIs.
     - **Reading:** [Jest Docs](https://jestjs.io/docs/getting-started)
     - **Video:** [Testing React Apps](https://www.youtube.com/watch?v=8Xwq35cPwYg)
  2. Deploy the frontend to Netlify or Vercel.
     - **Reading:** [Netlify Deployment Guide](https://docs.netlify.com/)
     - **Video:** [Deploying React Apps](https://www.youtube.com/watch?v=eSeBVcKZx9Y)
  3. Deploy the backend to Render or AWS.
     - **Reading:** [Render Deployment Docs](https://render.com/docs)
     - **Video:** [Node.js Deployment](https://www.youtube.com/watch?v=l134cBAJCuc)

- **Deliverables:**
  - Fully tested and deployed Product Store app.

---
## **Screenshots**
![Screenshot (375)](https://github.com/user-attachments/assets/c43c907c-623f-4289-917f-7ff7f36342a1)
![Screenshot (376)](https://github.com/user-attachments/assets/4787cd49-5368-46f8-83fa-2f028ebbef8c)
![Screenshot (377)](https://github.com/user-attachments/assets/babcbe19-531d-43d3-a10b-e448f5236b9c)
![Screenshot (372)](https://github.com/user-attachments/assets/24eb054a-c577-4d8e-8887-4692444cb334)
![Screenshot (373)](https://github.com/user-attachments/assets/cb2b2a72-3967-4c5b-969d-bfb72c3d7573)
![Screenshot (374)](https://github.com/user-attachments/assets/904dcf17-16d9-4428-a2f6-3935f7a5476f)

---

## **References**
1. [React Documentation](https://react.dev/blog/2023/03/16/introducing-react-dev)
2. [MongoDB Documentation](https://www.mongodb.com/docs/manual/)
3. [Stripe Documentation](https://stripe.com/docs)
4. [Netlify Documentation](https://docs.netlify.com/)
5. [Express Documentation](https://expressjs.com/)
6. https://www.youtube.com/watch?v=KOuPaj_bXAk
7. https://github.com/meprashantkumar/pinterest-clone

