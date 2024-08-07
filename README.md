### Book Advisor 📚

#### Overview
Book Advisor is a web application that offers personalized book recommendations based on users reading preferences. Leveraging data from the New York Times Bestseller lists and integrating with the Google Books API, Book Advisor provides a seamless experience for discovering new reads. The system consists of both frontend and backend components, with the frontend built using React.js and the backend powered by Flask.

#### Features
- View current New York Times bestsellers for both fiction and nonfiction.
- Receive tailored book recommendations based on your reading history.
- Search for books by title, author, or genre.
- Access detailed book information including cover images, ratings, and publication details.
- Save favorite books to your profile for future reference.

### Backend (BookAdvisor)

#### Prerequisites
- Python 3.10.x or later
- `venv` module version 3.3 or later
- MongoDB installed and running locally

#### Setup
1. Navigate to the `backend` (https://github.com/NikKnez/Book_Advisor_Project/tree/main/backend) directory.
2. Create a virtual environment using `python -m venv .` and activate it.
3. Install dependencies using `pip install -r requirements.txt`.
4. Set environment variables for database credentials, mail server details, Google Books API key (https://developers.google.com/books), and New York Times API key (https://developer.nytimes.com/).
5. Run the Flask server using `python app.py`.

### Frontend (book_advisor_frontend)

#### Prerequisites
- Node.js 16.x and npm

#### Development
1. Navigate to the `frontend` (https://github.com/NikKnez/Book_Advisor_Project/tree/main/frontend) directory.
2. Install dependencies using `npm install`.
3. Set the `REACT_APP_API_ENDPOINT` variable in the `.env` file to the URL of the backend server (by default this is `http://127.0.0.1:5000/`).
4. Start the development server using `npm start`.

## Screenshots

![Screenshot_1](frontend/src/images/Screenshot_1.png)

![Screenshot_2](frontend/src/images/Screenshot_2.png)

![Screenshot_3](frontend/src/images/Screenshot_3.png)

![Screenshot_4](frontend/src/images/Screenshot_4.png)

![Screenshot_5](frontend/src/images/Screenshot_5.png)

![Screenshot_6](frontend/src/images/Screenshot_6.png)

![Screenshot_7](frontend/src/images/Screenshot_7.png)

![Screenshot_8](frontend/src/images/Screenshot_8.png)

![Screenshot_9](frontend/src/images/Screenshot_9.png)

## 🌐 Live Demo

[Check out the live demo](https://bookadvisor.netlify.app) of the Book Advisor.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request for any enhancements or bug fixes.


**Developed by [NikKnez](https://github.com/NikKnez)**
