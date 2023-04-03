# Daily-Affirmations-
Self Help Side Project 
# Daily Affirmation Text Messages

This is a Python application that sends daily affirmations as text messages to your cell phone.

## Prerequisites

- Python 3.6 or higher
- Twilio API account and authentication token

## Installation and Setup

1. Clone the repository to your local machine using `git clone https://github.com/yourusername/daily-affirmations.git`
2. Install the required packages by running `pip install -r requirements.txt`
3. Create a `.env` file and add your Twilio API account SID and authentication token:

    ```
    TWILIO_ACCOUNT_SID=your_account_sid
    TWILIO_AUTH_TOKEN=your_auth_token
    ```

4. Edit the `config.py` file to add your phone number and Twilio phone number.
5. Run the application using `python app.py`

## Usage

To use the application:
1. Run the application using `python app.py`
2. The application will send a random affirmation to your phone number at the scheduled time.
3. To customize the list of affirmations, edit the `affirmations.txt` file. Each affirmation should be on a separate line.

## Contributions

Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request or open an issue on GitHub.

If you would like to contribute, please follow these steps:

1. Fork the repository to your GitHub account
2. Clone the forked repository to your local machine
3. Create a new branch for your changes
4. Make your changes and commit them with a descriptive message
5. Push the changes to your GitHub repository
6. Create a pull request on the original repository

We welcome contributions of all kinds, including bug fixes, new features, and improvements to documentation or test coverage.

Before making significant changes, please create an issue on GitHub to discuss your ideas and ensure they align with the project goals.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

