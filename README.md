# MERN Stack Personal Finance Manager

This is a full-stack web application for managing personal finances, built using the **MERN (MongoDB, Express, React, Node.js)** stack. It provides a simple and intuitive way to track income and expenses, categorize transactions, and visualize your financial health.

-----

### Features

  * **User Authentication:** Secure user registration and login.
  * **Transaction Management:** Easily add new income and expense entries with details like amount, date, and description.
  * **Categorization:** Assign categories (e.g., Food, Salary, Rent) to each transaction for better organization.
  * **Data Visualization:** Interactive charts (e.g., circular charts) provide a visual breakdown of spending and income.
  * **Filtering & Analysis:** Filter transactions by category and time period to gain insights into your spending habits.

-----

### Technologies Used

  * **Frontend:**
      * **React:** For building the user interface.
      * **Chart.js / D3.js:** (or a similar library) for data visualization.
  * **Backend:**
      * **Node.js & Express:** For the server and RESTful API.
  * **Database:**
      * **MongoDB:** NoSQL database for storing user and financial data.
      * **Mongoose:** ODM library for schema modeling.
  * **Authentication:**
      * **JWT (JSON Web Tokens):** For secure API authentication.
      * **Bcrypt:** For password hashing.
  * **Development Tools:**
      * **Git & GitHub:** For version control.

-----

### Installation and Setup

To run this project locally, you must have **Node.js** and **MongoDB** installed on your machine.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```
2.  **Install dependencies for both frontend and backend:**
    ```bash
    # Install server dependencies
    npm install

    # Change into the client directory (if applicable) and install
    cd client  # or similar folder name
    npm install
    cd ..
    ```
3.  **Set up environment variables:**
      * Create a `.env` file in the project's root directory.
      * Add your MongoDB connection string and a JWT secret.
    <!-- end list -->
    ```env
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=a_secure_secret_key
    ```
4.  **Start the application:**
    ```bash
    # Start the backend server
    npm start

    # In a new terminal, start the React frontend
    npm run dev  # or similar command based on your setup
    ```
5.  **Access the application:**
      * Open your browser and navigate to `http://localhost:3000` to view the application.

-----

### License

This project is licensed under the MIT License.
