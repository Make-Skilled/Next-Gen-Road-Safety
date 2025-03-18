# Live Object Detection with YOLO

This Flask application provides real-time object detection using YOLO (You Only Look Once) with a web interface.

## Features
- Live camera feed with object detection
- User authentication (login/signup)
- Object detection history tracking
- Modern UI with Tailwind CSS

## Setup Instructions

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Initialize the database:
```bash
python init_db.py
```

4. Run the application:
```bash
python main.py
```

5. Open your browser and navigate to `http://localhost:5000`

## Requirements
- Python 3.8+
- Webcam access
- Modern web browser 