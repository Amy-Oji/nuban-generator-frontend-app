# NUBAN Generator Frontend App

This is a frontend application that provides a user interface for generating Nigerian Uniform Bank Account Numbers (NUBAN) based on bank institution codes and serial numbers. It interacts with the NUBAN Generator Backend App to perform the NUBAN generation.

## Features

- Generates NUBANs based on provided bank institution codes and serial numbers.
- Sends requests to the NUBAN Generator Backend App for NUBAN generation.
- Displays the generated NUBAN or any error messages received from the backend.

## Technologies Used

- HTML
- CSS
- JavaScript
- AngularJS

## Getting Started

To get started with the NUBAN Generator Frontend App, follow these steps:

1. Clone the repository:

   ```shell
   git clone git@github.com:Amy-Oji/nuban-generator-frontend-app.git
   ```

2. Navigate to the project directory:

   ```shell
   cd nuban-generator-frontend
   ```

3. Open the `index.html` file in a web browser or host the project on a web server.

## Usage

1. Open the NUBAN Generator Frontend App in a web browser.

2. Enter a valid bank institution code (issued by CBN) in the input field labeled "Bank Institution Code".

3. Enter a serial number of not more than 9 digits in the input field labeled "Serial Number".

4. Click the "Generate NUBAN" button.

5. The app will send a request to the NUBAN Generator Backend App with the provided bank code and serial number.

6. If the backend responds with a generated NUBAN, it will be displayed below the "Response From NUBAN Generator Backend:" heading.

7. If there is an error, such as an invalid bank code, the error message will be displayed below the "Response From NUBAN Generator Backend:" heading.

