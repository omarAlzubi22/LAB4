Setup Instructions:

1. Running the Flask Server
The Flask server is defined in the file my-server.py. It runs locally on port 5000. To start the server:

     First, ensure that the required dependencies (Flask) are installed in your Python environment. Then, open a terminal or command line and navigate to the directory where the my-server.py file is located. Run the file. Once the server is running, it will be accessible locally at 'http://localhost:5000.'

2. Running the Client Script
The client script (my-calls.py) interacts with the running Flask server. It performs two operations:

     Logs in with predefined credentials.
If the login is successful, it sends a POST request to the /echo endpoint with a message.
To run the client script, make sure httpx is installed in your Python environment. Then, run the my-calls.py script, which will attempt to log in and send a message if successful.

3. Testing the Server
     Login: The /login route expects a POST request with an id and token in the form data. If the credentials match, a successful login message will be returned. If the credentials are incorrect, an error message will be returned.
     Echo: The /echo route allows you to send a message and echoes back the content of the message that was sent.
