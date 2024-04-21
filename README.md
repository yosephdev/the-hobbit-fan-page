# The Hobbit Fan Page: Thorin and Company

This is a Flask web application that serves as a fan page for Thorin Oakenshield and his company of dwarves from J.R.R. Tolkien's beloved novel, The Hobbit. The app provides information about the characters, their quest, and allows fans to share their thoughts and appreciation.

## Features

- **Character Profiles:** Detailed profiles of Thorin and each member of his company, including their backgrounds, personalities, and roles in the quest.
- **Quest Overview:** A comprehensive overview of the dwarves' quest to reclaim the Lonely Mountain from the dragon Smaug. [Quest Overview](external-link)
- **Fan Forum:** A dedicated section within the application that displays recent discussions and allows users to start new discussions. The forum includes the following features:
  - **Recent Discussions:** A list of recent discussions or forum posts, each displaying the title, a brief description, and the name of the user who posted it along with the date.
  - **Start a New Discussion:** A form where users can enter a topic and message to start a new discussion.

## Planned Features

- **Fan Forum:** While the application doesn't have a fully-fledged custom fan forum, it provides a section that simulates the experience of a fan forum by displaying sample discussions and allowing users to submit new discussion topics and messages through a form.

## Technologies Used

- Flask: A lightweight Python web framework used for building the application.
- HTML/CSS: Markup and styling languages for creating the user interface.
- JSON: Data interchange format used for communication between the backend and frontend of the application.

## Steps to Build the Application

To build the application locally, follow these steps:

1. **Clone the repository:**

   ```bash

   git clone https://github.com/your-username/the-hobbit-fan-page.git

   ```

2. **Navigate to the project directory:**

   ```bash

   cd the-hobbit-fan-page

   ```

3. **Create and activate a virtual environment (optional but recommended):**

   ```bash
   python -m venv env
   source env/bin/activate

   On Windows, use `env\Scripts\activate`

   ```

4. **Install the required dependencies:**

   ```bash

   pip install -r requirements.txt

   ```

5. **Set up the database:**

   ```bash

   flask db upgrade

   ```

6. **Run the application:**

   ```bash

   flask run

   ```

7. Open your web browser and visit <http://localhost:5000> to access the fan page.

## Steps to Deploy the Application

Follow these steps to deploy the app:

1. **Sign up for Heroku:** If you haven't already, create a Heroku account [here](https://signup.heroku.com/).

2. **Install Heroku CLI:** Download and install the Heroku Command Line Interface (CLI) from [here](https://devcenter.heroku.com/articles/heroku-cli).

3. **Log in to Heroku:** Open your terminal or command prompt and log in to Heroku using the command `heroku login`.

4. **Create a new Heroku app:** Once logged in, create a new Heroku app by running `heroku create your-app-name` in your terminal. Replace `your-app-name` with the desired name of your app.

5. **Deploy your code:** After setting up your Heroku app, deploy your code to Heroku by executing `git push heroku master` in your terminal. This command pushes your local Git repository to Heroku's servers.

6. **Access your deployed app:** Once deployment is complete, open your browser and navigate to the URL provided by Heroku, or use the command `heroku open` in your terminal to open the app automatically.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your forked repository.
5. Submit a pull request to the main repository.

## Acknowledgments

- J.R.R. Tolkien for creating the incredible world of Middle-earth and the beloved characters from The Hobbit.
- Tim Nelson, Software Developer and Tutor at Code Institute, for preparing and presenting the walkthrough of the application
- The Flask community for their excellent documentation and support.
- All the contributors who have helped make this project better.
