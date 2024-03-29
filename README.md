# Addis Software Test Project - Backend

This is the backend part of the Addis Software Test Project, a MERN stack application for managing information about songs.

## Technologies Used

- **Express.js**: Handling HTTP requests.
- **MongoDB**: Database for storing song data.
- **Mongoose**: Interacting with MongoDB and defining schemas.
- **Docker**: Packaging the backend application.
  
## Getting Started

To run the backend server locally, follow these steps:

1. Clone this repository.
2. Navigate to the `backend` directory.
3. Install dependencies: `npm install`.
4. Start the server: `npm start`.

The server will run on `http://localhost:3000` by default.

## API Endpoints

- `GET /songs`: Get all songs.
- `GET /songs/:id`: Get a specific song by ID.
- `POST /songs`: Create a new song.
- `PUT /songs/:id`: Update an existing song.
- `DELETE /songs/:id`: Delete a song.

For detailed usage of each endpoint, refer to the API documentation.

## Docker

You can also run the backend using Docker:

1. Build the Docker image: `docker build -t song-manager-backend .`
2. Run the Docker container: `docker run -p 3000:3000 song-manager-backend`

## Contribution

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or create a pull request.


 
 
