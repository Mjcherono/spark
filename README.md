# Spark
# PySpark Project

## Overview
This project is a quick implementation of PySpark for data processing and analysis. It utilizes a Docker image for Spark, ensuring a consistent environment across different setups.

## Table of Contents
- [Requirements](#requirements)
- [Docker Setup](#docker-setup)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Requirements
Ensure you have the following requirements installed:

- Python 3.x
- Docker
- Docker Compose

All project-specific dependencies are listed in the `requirements.txt` file.

## Docker Setup
To get started, you'll need to set up Docker. If you haven't already installed Docker, follow the instructions on the [official Docker documentation](https://docs.docker.com/get-docker/).

### Pulling the Docker Image
1. Pull the official Spark Docker image:
    ```bash
    docker pull spark
    ```

### Running the Docker Image
1. Clone this repository:
    ```bash
    git clone https://github.com/Mjcherono/spark.git
    ```

2. Navigate into the cloned directory:
    ```bash
    cd spark  # Replace with 'spark' if you cloned it directly
    ```

3. Start the Docker container:
    ```bash
    docker run -it --rm -v "$(pwd)":/app -w /app spark /bin/bash
    ```

## Installation
### Running Jupyter Notebook Files
1. Install Jupyter Notebook (if not included in your `requirements.txt`):
    ```bash
    pip install notebook
    ```

2. Start Jupyter Notebook:
    ```bash
    jupyter notebook --ip=0.0.0.0 --allow-root
    ```

3. Install project dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

### Key Changes:
- Updated the **Pulling the Docker Image** section to pull the Spark Docker image directly.

Feel free to make any additional adjustments, and let me know if you need further modifications or help!
