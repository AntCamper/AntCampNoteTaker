#ANTCAMPNOTETAKER

##DESCRIPTION
This Note Taker application allows users to write, save, and delete notes. It uses an Express.js back end and saves and retrieves note data from a JSON file.

##Installation

1.Clone the repository: https://github.com/AntCamper/AntCampNoteTaker.git
2.Navigate to the directory
3.Install dependencies 
npm install
## Usage
to use this locally:
1.Start the server in your terminial run: node server.js
2. Open your web browser and go to http://localhost:3000
3. Click on the "Get Started" button to start taking notes
4. To add a new note, click on the pencil icon and enter a title and text
5. To save a note, click on the save icon (floppy disk)
6. To view a saved note, click on it in the left-hand column
7. To delete a note, click on the trash can icon next to the note

## Deployed Application
The application is deployed on Heroku and can be accessed at:

[https://antcampnotetaker-2eb08fd92511.herokuapp.com/](https://antcampnotetaker-2eb08fd92511.herokuapp.com/)

You can use the application directly through this link without need for local installation.

## Technologies Used

- HTML
- CSS
- JavaScript
- Node.js
- Express.js
- Uniqid (for generating unique IDs)
- Heroku (for deployment)

## API Routes

- GET `/api/notes` - Retrieves all saved notes
- POST `/api/notes` - Adds a new note
- DELETE `/api/notes/:id` - Deletes a note with the specified ID
