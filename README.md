# QR-Code-Generator

### Introduction

The QR Code Generator is a command-line application that prompts the user for a URL, generates a QR code image for the provided URL, and saves the URL in a text file.

### Features

- Prompt the user for a URL input.
- Generate a QR code image from the provided URL.
- Save the QR code image as qr_image.png.
- Save the URL in a text file named message.txt.
  
### Technologies Used

- Node.js - JavaScript runtime for executing server-side code.
- Inquirer - For command-line user input.
- qr-image - For generating QR code images.
- fs (File System) - For file operations.
  
### Installation

#### Prerequisites

- Node.js installed on your system.
  
#### Steps

- Clone the repository:
  
         git clone https://github.com/yourusername/qr-code-generator.git
  
- Navigate to the project directory:

         cd qr-code-generator
  
- Install the required npm packages:

         npm install
  
#### Usage

- Run the application:

         node index.js
  
- Follow the prompt to enter a URL.
- The application will generate a QR code image (qr_image.png) and save the URL in message.txt.
