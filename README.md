# Auto-Scaling Flask App  

This project deploys a Flask application on a local VM and automatically scales it to GCP when CPU usage exceeds 75%.  

## Files  
- **app.py** – Flask application that simulates high CPU usage.  
- **monitor_resource.sh** – Script to monitor CPU usage and trigger auto-scaling to GCP.  

## Usage  

### 1️⃣ Run the Flask Application  
```bash
python3 app.py
```
### 2️⃣ Start Resource Monitoring & Auto-Scaling
```bash
chmod +x monitor_resource.sh  
./monitor_resource.sh
```
