Simple weather app built using Django. 
It fetches real-time weather data for the current location entered by the user and displays details such as temperature, humidity, and precipitation. 
The app uses an external weather API to fetch weather information and display it in a user-friendly interface.

To get this project up and running on your local machine, follow these steps:

Clone the repository:

1. Create a virtual environment (optional but recommended):
git clone https://github.com/rhoda-asu/weather_app.git
cd weather_app

3. python3 -m venv venv
Activate the virtual environment:

4. Install dependencies:
pip install -r requirements.txt

5. Set up environment variables: You will need to create a .env file in the root of the project directory to store your weather API key:
WEATHER_API_KEY=your_api_key_here

6.Run the app:
python(3) manage.py runserver
The app should now be running locally at http://127.0.0.1:8000.
