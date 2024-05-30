# HBNB

## Description
HBNB is a full web application, integrating database storage, a back-end API, and front-end interfacing in a clone of AirBnB. This repository contains the codebase for the project, which involves various key features such as user authentication, dynamic content display, and data management.

## Repository Contents

### Directories
- **models/**: Contains all the data models for the project, including base models and specific model definitions.
- **web_static/**: Contains static HTML, CSS, and images for the web interface.
- **tests/**: Contains all test cases for the project.

### Files
- **console.py**: The command line interpreter for managing the application.
- **README.md**: This file.

## Getting Started

### Prerequisites
- Python 3.x
- pip

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/mhlibya/hbnb.git
    cd hbnb
    ```
2. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
To start the console:
```sh
./console.py

# Console description and how to use

## quit:
* Exists the interpreter.

## EOF:
* Handles the EOF (Ctrl+D) to exit the interpreter.

## create:
* Creates a new instance of a given model.
#### Arguments:
* Class name.

## show:
Shows an instance based on class name and ID.
#### Arguments:
Class name and instance ID.

## destroy:
* Deletes an instance based on class name and ID.
#### Arguments:
* Class name and instance ID.

## all:
Shows all instances of a specified class or all instances if no class is specified.
#### Arguments: (Optional)
* Class name.

## update:
Updates an instance`s attribute based on class name, ID, attribute name, and value.
#### Arguments:
* Class name, instance ID, attribute name, and value.
