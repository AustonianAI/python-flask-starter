# Flask Docker Development Template

This is a template for a simple Flask application running inside a Docker container with hot-reloading enabled for development.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development purposes.

1. Clone the repository:

   ```bash
   git clone https://github.com/AustonianAI/flask-docker-template.git
   ```

2. Navigate into the cloned repository:

   ```bash
   cd flask-docker-template
   ```

3. Build the Docker images:

   ```bash
   docker-compose build
   ```

4. Start the Docker containers:

   ```bash
   docker-compose up
   ```

The Flask application will be accessible at `http://localhost:5000`.

## Development

The Flask application runs inside a Docker container, with hot-reloading enabled. This means that when you make changes to your Python files, the application will automatically restart and your changes will immediately take effect.

The hot-reloading functionality is provided by `watchdog` and `watchmedo`. These tools are set up to watch the Python files in your application and restart the Flask server whenever a file changes.

## Built With

- [Python 3.11](https://www.python.org/)
- [Flask](https://flask.palletsprojects.com/)
- [Docker](https://www.docker.com/)
- [watchdog](https://pythonhosted.org/watchdog/)

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/AustonianAI/8b692731859d4b76670004b50c02ee8c) for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- Thanks to the Python, Flask, and Docker communities for their awesome tools!
