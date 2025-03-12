CAD-Viewer

A web-based application that allows users to upload, view, and manipulate 3D models (e.g., .obj or .stl files) directly in the browser. Built using React, Three.js, and Flask.

Features

Upload and visualize 3D models in .obj and .stl formats.

Interactive controls to rotate, zoom, and pan models.

Export models to different formats (e.g., .obj to .stl).

Modern and user-friendly interface for seamless navigation.


Technologies Used

Frontend: React, Three.js

Backend: Flask

Styling: CSS


Prerequisites

Ensure you have the following installed before running the application:

Node.js (for the frontend)

Python (for the backend)

pip (Python package manager)


Installation and Setup

1. Clone the Repository

git clone https://github.com/your-username/cad-viewer.git
cd cad-viewer

2. Backend Setup

Navigate to the backend folder:

cd backend

Create a virtual environment (optional but recommended):

python -m venv venv

Activate the virtual environment:

Windows:

venv\Scripts\activate

macOS/Linux:

source venv/bin/activate


Install dependencies:

pip install -r requirements.txt

Start the Flask backend:

python app.py

The backend runs on http://127.0.0.1:5000.

3. Frontend Setup

Open a new terminal and navigate to the frontend folder:

cd ../frontend

Install dependencies:

npm install

Start the React frontend:

npm start

The frontend runs on http://localhost:3000.

Running the Application

1. Open http://localhost:3000 in your browser.


2. Upload a 3D model file (.obj or .stl).


3. Interact with the model using:

Left-click + drag → Rotate

Right-click + drag → Pan

Scroll → Zoom



4. Use the export feature to download the model in a different format.



This application provides an intuitive interface for working with 3D models in the browser. Enjoy exploring your designs!
