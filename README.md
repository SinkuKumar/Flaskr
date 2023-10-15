# Flaskr - A Flask Tutorial Application

This repository contains the Flaskr application, which is a simple blog application created by following the official Flask tutorial.

## Getting Started

### Prerequisites

To run this application, you'll need the following:

- Python 3.x installed on your system
- Flask framework

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SinkuKumar/Flaskr.git
   cd Flaskr
   ```

2. Create a virtual environment and activate it:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Initialize the database:
   ```bash
   flask init-db
   ```

5. Run the application:
   ```bash
   flask run
   ```

## Testing

To run tests for this application, use the following command:
```bash
pytest
```

The tests are located in the `tests/` directory.

## Usage

Access the application in your web browser at `http://localhost:5000`.

## Contributing

If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository on GitHub.
2. Create a new branch for your changes.
3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your fork.
5. Submit a pull request with a detailed explanation of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
