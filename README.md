# Healthcare Dashboard

A simple dashboard built with **React** (frontend) and **Flask** (backend) for healthcare data submission. Users can input their name, age, and upload files like medical reports.

## **Technologies Used**
- **Frontend**: React.js
- **Backend**: Flask (Python)
- **File Upload**: FormData (React) and Flask `request.files`

## **Setup Instructions**

### **1. Backend (Flask) Setup**

1. Go to the `flask` folder in your terminal.
2. Install Flask and CORS:
   ```bash
   pip install flask flask-cors
   ```
3. Create an `uploads` folder to store uploaded files.
4. Run the Flask app:
   ```bash
   python app.py
   ```

### **2. Frontend (React) Setup**

1. Go to the `react` folder in your terminal.
2. Install the required dependencies:
   ```bash
   npm install
   ```
3. Start the React app:
   ```bash
   npm start
   ```

## **How to Use**

1. Open `http://localhost:3000` (React app) in your browser.
2. Enter your **Name** and **Age**.
3. Choose a **File** to upload.
4. Click **Submit** to send the data to the server.

