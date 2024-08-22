# PIXIO-E-COMMERCE-DIGITAL-PLATFORM
# Pixio 🎨

Welcome to **Pixio**, your ultimate e-commerce platform for digital creators! 🚀 This web application allows artists and creators to showcase and sell their digital products with ease. Built on the robust MERN stack, Pixio delivers a seamless user experience with top-notch performance.

## Features ✨

- **User Authentication** 🔐: Secure login and registration.
- **Product Management** 🛒: Easily manage your digital products.
- **Order Processing** 📦: Streamlined checkout and payment handling.
- **Responsive Design** 📱: Optimized for all devices.
- **AWS Integration** ☁️: Deployed on a scalable cloud platform.

## Getting Started 🚀

To run Pixio locally, follow these steps:

### Prerequisites

Ensure you have the following installed on your system:

- **Node.js** (v14 or above) 🌐
- **MongoDB** (local or Atlas) 🗄️
- **npm** or **yarn** (latest version) 📦

### Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/pixio.git
    cd pixio
    ```

2. **Install dependencies for the client**:

    Navigate to the client directory:

    ```bash
    cd client
    ```

    Then, install the necessary packages:

    ```bash
    npm install
    ```

3. **Install dependencies for the server**:

    Navigate back to the root directory and into the server directory:

    ```bash
    cd ../server
    ```

    Install the required packages:

    ```bash
    npm install
    ```

### Running the Application 🏃

To start the application, you'll need to run both the client and server concurrently:

1. **Start the server**:

    In the `server` directory, run:

    ```bash
    npm start
    ```

    This will start the backend server on `http://localhost:5000`.

2. **Start the client**:

    In a new terminal window, navigate back to the `client` directory:

    ```bash
    cd ../client
    ```

    Then, run:

    ```bash
    npm start
    ```

    This will start the frontend React application on `http://localhost:3000`.

### Environment Variables ⚙️

Ensure you set up the necessary environment variables in a `.env` file within the `server` directory:

```env
MONGO_URI=your_mongo_db_connection_string

