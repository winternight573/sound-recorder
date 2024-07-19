# Sound Recorder App

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [License](#license)
- [Contact](#contact)

## Introduction

This is a sound recorder app built using React Native for the frontend and Go for the backend. The app allows users to record audio, playback recordings, upload recordings to a database, view a list of recorded files, and delete chosen recordings. The project utilizes MySQL for the database, Docker for containerization, and Amazon S3 for cloud storage.

## Features

- **Playback**: Play recorded audio files.
- **Record**: Record new audio files.
- **Upload**: Upload recorded audio files to the database.
- **View List**: View a list of all recorded audio files.
- **Delete**: Delete selected audio recordings.

## Tech Stack

- **Frontend**: React Native
- **Backend**: Go
- **Database**: MySQL
- **Containerization**: Docker
- **Cloud Storage**: Amazon S3

## Installation and Setup

Currently, detailed installation steps are not provided due to the small scale of the project. Basic steps to get started might include:

1. **Clone the repository**

   ```sh
   git clone https://github.com/username/sound-recorder-app.git
   ```

2. **Install frontend dependencies**

   ```sh
   cd sound-recorder-app/frontend
   npm install
   ```

3. **Install backend dependencies**

   ```sh
   cd ../backend
   go mod tidy
   ```

4. **Run the frontend**

   ```sh
   cd frontend
   npm start
   ```

5. **Run the backend**

   ```sh
   cd backend
   go run main.go
   ```

6. **Docker Setup**
   - Build and run the Docker containers for the backend and MySQL

   ```sh
   docker-compose up --build
   ```

## Usage

### Recording Audio

1. Open the app and navigate to the record screen.
2. Press the record button to start recording.
3. Press the stop button to stop recording.

### Playback

1. Navigate to the list of recorded files.
2. Select a file and press the play button to playback.

### Upload

1. After stopping the recording, the app will automatically upload the file to the database and S3.

### View List

1. Navigate to the list of recorded files to view all recordings.

### Delete

1. Select a recording from the list.
2. Press the delete button to remove the selected recording.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Contact

If you have any questions, please contact:

- Email: <Maverickwinnie573@gmail.com>
- GitHub: [winternight573](https://github.com/winternight573)

---

This streamlined version should cover the essentials for your project without overwhelming you with setup details or contribution guidelines. Feel free to add more information as your project grows!
