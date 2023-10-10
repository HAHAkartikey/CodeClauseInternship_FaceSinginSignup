# Face Signin Signup Project

This is a Face Signin Signup project that allows users to sign up and sign in using their facial recognition. The project is built using a combination of HTML, CSS, JavaScript, and Python. It leverages popular libraries like TensorFlow, os, numpy, decouple, and pymongo to achieve its functionality.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

In today's digital world, security is of utmost importance. Traditional username and password authentication methods have their vulnerabilities, which is where facial recognition comes into play. This project aims to provide a more secure and user-friendly authentication system by allowing users to sign up and sign in using their facial features.

## Features

- **Face Signin**: Users can sign in to their accounts by scanning their faces using a webcam or uploaded image.
- **Face Signup**: Users can create new accounts by scanning their faces and providing necessary information.
- **Secure**: Facial recognition provides a secure authentication method, reducing the risk of unauthorized access.
- **User Data Storage**: User data is stored in a MongoDB database for easy retrieval and management.
- **Web-based Interface**: The project provides a web-based interface for users to interact with the system.

## Prerequisites

Before you can use this project, you will need the following prerequisites:

- Python installed on your machine (Python 3.7 or higher recommended).
- Required Python libraries installed (TensorFlow, numpy, decouple, pymongo).
- A webcam (if you plan to use real-time face recognition).
- A MongoDB database (local or remote) to store user data.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/HAHAkartikey/CodeClauseInternship_FaceSigninSignup.git
   ```

2. Install the required Python libraries:

   ```bash
   pip install tensorflow numpy decouple pymongo
   ```

3. Create a `.env` file in the project root directory and add your MongoDB connection URL and other sensitive data. You can use the `sample.env` file as a template.

4. Start the Python server:

   ```bash
   python server.py
   ```

5. Open the project in your web browser:

   ```
   http://localhost:8080
   ```

## Usage

1. Visit the web interface and click on the "Sign Up" option to create a new account.
2. Follow the on-screen instructions to scan your face and provide necessary information.
3. After successful registration, you can use the "Sign In" option to log in by scanning your face.

## Contributing

If you want to contribute to this project, feel free to fork the repository and submit pull requests. You can also open issues for bug reports or feature requests.

---

**Note:** Remember to keep your `.env` file and sensitive information secure. This project should be used for educational and non-commercial purposes.
