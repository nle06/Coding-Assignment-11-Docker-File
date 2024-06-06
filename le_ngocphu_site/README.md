# Codin 1 React App

This project is a simple React application that displays a <h1> tag with the text “Codin 1”.

## Getting Started

These instructions will help you get the web application running on your local machine using Docker.

### Prerequisites

- Docker installed on your machine.

### Building the Docker Image

1. Clone the repository or navigate to your project directory.
2. Open a terminal and build the Docker image with the following command:

    ```sh
    docker build -t le_ngocphu_coding_assignment11 .
    ```

### Running the Docker Container

1. After the image is built, run the container with the following command:

    ```sh
    docker run -d -p 7775:3000 --name le_ngocphu_coding_assignment11 le_ngocphu_coding_assignment11
    ```

2. Open your web browser and go to `http://127.0.0.1:7775`. You should see the webpage displaying the text “Codin 1”.

### Project Structure

- `Dockerfile`: Contains the instructions to build the Docker image.
- `README.md`: Contains the instructions to get the application running.
- `src`: Contains the source code for the React application.

### React Application Code

Here is the code for the basic React application:

```javascript
// src/App.js

import React from 'react';

function App() {
  return (
    <div className="App">
      <h1>Codin 1</h1>
    </div>
  );
}

export default App;
