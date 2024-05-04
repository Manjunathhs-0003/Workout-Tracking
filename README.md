<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>Workout Tracking Project</h1>

<h2>Overview:</h2>
<p>
    The workout tracking project utilizes Sheety API and Google Sheets to track and record users' workout activities.
    Users can input their exercise details, such as exercise name, duration, and the data is stored
    in a Google Sheets spreadsheet via Sheety API.
</p>

<h2>Features:</h2>
<ul>
    <li>User-friendly command-line interface for entering workout details.</li>
    <li>Automatic recording of workout data in a Google Sheets spreadsheet.</li>
    <li>Real-time tracking of exercise name, duration, and calories burned.</li>
</ul>

<h2>How the Project Works:</h2>
<ol>
    <li><strong>User Input:</strong> Users input their exercise details, including exercise name, duration through a command-line interface.
    </li>
    <li><strong>Nutritionix API:</strong> The entered exercise details are sent to the Nutritionix API to retrieve
        nutritional information.
    </li>
    <li><strong>Sheety API:</strong> The retrieved exercise data is then sent to the Sheety API, which stores it in a
        Google Sheets spreadsheet.
    </li>
    <li><strong>Google Sheets:</strong> The workout data is updated in real-time in the Google Sheets spreadsheet,
        allowing users to track their exercise activities.
    </li>
</ol>

<h2>Installation Guide:</h2>
<ol>
    <li><strong>Clone the Repository:</strong></li>
    <p>
        git clone https://github.com/Manjunathhs-0003/Workout-Tracking.git
    </p>
    <li><strong>Navigate to the Project Directory:</strong></li>
    <p>
        cd workout-tracking-project
    </p>
    <li><strong>Install Required Libraries:</strong></li>
    <p>
        pip install requests
    </p>
    <li><strong>Set Up API Keys and Endpoints:</strong></li>
    <p>
        Obtain API keys and endpoints for Sheety API and Google Sheets API as mentioned in the documentation.
    </p>
    <li><strong>Update Python Script:</strong></li>
    <p>
        Replace the placeholder API keys and endpoints in your Python script with the actual ones obtained from the
        documentation.
    </p>
    <li><strong>Run the Script:</strong></li>
    <p>
        python main.py
    </p>
</ol>

<h2>APIs Used:</h2>
<ul>
    <li><strong>Sheety API:</strong> Used to interact with Google Sheets and store workout data.</li>
    <li><strong>Google Sheets API:</strong> Used to access and update Google Sheets spreadsheet data.</li>
    <li><strong>Nutritionix API:</strong> Used to retrieve nutritional information for exercises entered by users.</li>
</ul>

<h1>Workout Tracking Project Documentation</h1>

<h2>1. Obtain API Keys and Endpoints:</h2>
<p>
    <strong>Sheety API:</strong><br>
    Sign up or log in to Sheety (<a href="https://sheety.co/">https://sheety.co/</a>).<br>
    Create a new project or select an existing one.<br>
    In your project settings, you will find your Sheety API key.<br>
    You can also find the endpoint for your project, which you'll use to make requests to Sheety.<br>
    <br>
    <strong>Google Sheets API:</strong><br>
    Go to the Google Developers Console (<a href="https://console.developers.google.com/">https://console.developers.google.com/</a>).<br>
    Create a new project or select an existing one.<br>
    Enable the Google Sheets API for your project.<br>
    Create credentials for your project and download the JSON file containing your client secret.<br>
    You will use this file to authenticate requests to the Google Sheets API.
</p>

<h2>2. Install Required Libraries:</h2>
<p>
    You'll need the requests library to make HTTP requests in Python. You can install it using pip:
</p>
<pre><code>pip install requests</code></pre>

<h2>3. Set Up Python Script:</h2>
<p>
    You've already started with your Python script. Ensure you have the necessary imports, variables for user data
    (like gender, weight, height, age), and endpoints for the Sheety API and Nutritionix API.
</p>

<h2>4. Make Requests:</h2>
<p>
    Use the requests library to make POST requests to the Sheety API endpoint with workout data. You'll need to include
    the Sheety API key in the request headers.
</p>

<h2>5. Update Google Sheets:</h2>
<p>
    After receiving a successful response from Sheety, you can update your Google Sheets with the workout data.
    Use the Google Sheets API for this purpose. You'll need to authenticate your requests using the client secret JSON file.
</p>

<h2>Documentation:</h2>
<p>
    Here are the documentation links you can refer to for obtaining API keys and endpoints:
</p>
<ul>
    <li><strong>Sheety API Documentation:</strong> <a href="https://sheety.co/docs">Sheety Documentation</a></li>
    <li><strong>Google Sheets API Documentation:</strong> <a href="https://developers.google.com/sheets">Google Sheets API Documentation</a></li>
</ul>

</body>
</html>
