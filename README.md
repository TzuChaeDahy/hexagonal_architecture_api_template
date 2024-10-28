# Hexagonal Architecture API Template

This repository contains a Golang API template structured with Hexagonal Architecture, intended to serve as a foundational structure for scalable and maintainable applications.

## Overview

The hexagonal (or ports and adapters) architecture helps create applications that are easily adaptable to changes in their external dependencies, such as databases, APIs, or other external systems. This template separates business logic from infrastructure code, allowing for increased flexibility and testing.

## Features

- **Hexagonal Architecture**: Clean separation of core business logic from infrastructure and external dependencies.
- **Dependency Injection**: Use of interfaces to manage dependencies.
- **Easy Testing**: Business logic is isolated, making unit testing straightforward.
- **Template for REST API**: Out-of-the-box RESTful structure for easy endpoint creation.

## Getting Started

### Prerequisites

- **Golang**: Make sure you have [Golang](https://golang.org/doc/install) installed on your machine.

### Installation

1. Clone this repository:

    ```bash
    
    git clone https://github.com/TzuChaeDahy/hexagonal_architecture_api_template.git
    ```

2. Navigate to the project directory:

    ```bash
    
    cd hexagonal_architecture_api_template
    ```

3. Install dependencies:

    ```bash
    
    go mod tidy
    ```

### Usage

Run the API with:

```bash

go run main.go
```

## Project Structure
- `/core` - Contains business logic and interfaces (ports).
- `/adapters` - Contains adapters to external systems (e.g., databases, external APIs).
- `/config` - Configuration files and setup.
  
## Contributing
Feel free to fork this repository, create new features, or report issues.

## License
This project is licensed under the MIT License.
