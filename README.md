# Instagram-Giveaway-Selector

### Instagram Giveaway Selector

### Overview

The Instagram Giveaway Selector is a web application designed to select a random winner from a pool of Instagram users who have participated in a giveaway by tagging other users, liking a post, and following the author. The application uses a Python Flask backend to process Instagram data and a simple HTML front-end to display the results.

This project is a slightly revised version of Gaisin's Instacheck, adapted for specific use cases and enhanced with additional features.

### Features

Instagram Integration: Connects to Instagram to check user interactions with giveaway posts.

Giveaway Logic: Identifies users who tagged at least 3 unique users, liked the post, and follow the author.

Winner Selection: Randomly selects a winner from eligible users.

Responsive Front-End: Displays results and error messages in a user-friendly manner with animations.


### Back-End Setup

**Prerequisites**

Python 3.x

Flask

Instabot

python-dotenv for environment variable management


**Installation**

1. Clone the Repository:

git clone https://github.com/x0inna/Instagram-Giveaway-Selector.git
cd instagram-giveaway-selector


2. Install Dependencies:

pip install Flask instabot python-dotenv


3. Configure Environment Variables:

Create a .env file in the root directory of the project and add your Instagram credentials:

INSTA_USERNAME=your_instagram_username
INSTA_PASSWORD=your_instagram_password


4. Run the Application:

python app.py

The application will start on http://127.0.0.1:5000.



### Front-End Setup

**Requirements**

A web server or hosting service (e.g., WordPress, static site host)


**Integration**

1. Update the API Endpoint:

In index.html, replace https://your-username.pythonanywhere.com/run-giveaway with your actual deployed API URL.


2. Add to Your Website:

Upload index.html to your web server or integrate it into your WordPress site using a custom HTML block.




### Usage

1. Open the front-end page in a web browser.


2. The page will automatically fetch the giveaway result from the back-end API and display the winner or any errors.



### **Important Warning

Using bots or scripts to interact with Instagram's API can violate Instagram’s Terms of Service.

Risk of Account Suspension: Instagram actively monitors and may suspend accounts that use automated tools or scripts.

Compliance: Ensure your use of such tools complies with Instagram's policies and guidelines.

Security: Be cautious about sharing your Instagram credentials and ensure they are protected.


Use this application responsibly and at your own risk.**

### Troubleshooting

Ensure the Flask app is running and accessible at the specified API URL.

Verify Instagram credentials are correct and have the necessary permissions.

Check browser console for any JavaScript errors and Flask logs for server-side issues.


### Contributing

Feel free to submit issues or pull requests if you have improvements or suggestions.

### License

This project is licensed under the MIT License. See the LICENSE file for details.
