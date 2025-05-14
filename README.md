# Python File Manager API + CLI Tool

## Description
A Python Flask REST API and Command-Line Interface (CLI) tool that allows users to upload, list, download, and delete files remotely.  
This project simulates an enterprise-grade internal automation tool, showcasing API development, CLI integration, Dockerization, and deployment readiness.

---

## Features
- REST API (Flask)
- Command-Line Interface (CLI) using `argparse`
- Dockerized for production-ready deployment
- Supports:
  - Upload files
  - List uploaded files
  - Download files
  - Delete files

---

## Technologies Used
- Python 3.9+
- Flask
- Requests
- Argparse
- Docker

---

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/YadrielPereyra/file-manager-api.git
cd file-manager-api

Install Dependencies
pip install -r requirements.txt

Run the API (Locally)
python app.py
API will be available at http://localhost:5000.

CLI Tool Usage (Locally)
Upload a file
python cli.py upload --file example.txt

List uploaded files
python cli.py list

Download a file
python cli.py download --file example.txt

Delete a file
python cli.py delete --file example.txt
Note: Make sure the API is running before using the CLI tool.

Build Docker image
docker build -t file-manager-api .

Run Docker container
docker run -p 5000:5000 file-manager-api

Deployment Suggestions
	•	Deploy on Render.com using the Docker image.
	•	Or deploy on AWS EC2, DigitalOcean, or Heroku.

Author

Yadriel Pereyra

⸻

License

This project is licensed under the MIT License.
See the LICENSE file for details.

