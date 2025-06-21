# Sample Python Flask Application

This is a simple Flask web application that responds with "Hello, World!" when accessed.

## Project Structure

```
sample-python-app
├── app.py
├── requirements.txt
├── Dockerfile
└── README.md
```

## Prerequisites

- Python 3.x
- pip (Python package installer)
- Docker (optional, for containerization)

## Installation

1. Clone the repository or download the project files.
2. Navigate to the project directory.

```bash
cd sample-python-app
```

3. Install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

## Running the Application

To run the application locally, execute the following command:

```bash
python app.py
```

The application will be accessible at `http://127.0.0.1:5000`.

## Containerization with Docker

To build and run the application using Docker, follow these steps:

1. Build the Docker image:

```bash
docker build -t sample-python-app .
```

2. Run the Docker container:

```bash
docker run -p 5000:5000 sample-python-app
```

The application will be accessible at `http://127.0.0.1:5000`.

## License

This project is licensed under the MIT License.