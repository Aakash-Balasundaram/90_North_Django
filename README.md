# 90_North_Django

### **Steps for Running the AWS Django Project**

1. Activate Your Virtual Environment
Before running the Django development server, you need to activate your virtual environment (if you have one).

For Windows:
Open your terminal/command prompt and navigate to your project directory where the manage.py file is located.
Run the following command to activate the virtual environment:

.\venv\Scripts\activate
(Replace venv with the name of your virtual environment directory if it's different.)

For macOS/Linux:
Open your terminal and navigate to your project directory.
Run the following command to activate the virtual environment:

source venv/bin/activate
(Again, replace venv with the actual name of your virtual environment directory if needed.)

2. Navigate to the Django Project Directory
If you aren't already in the project directory, use the cd command to navigate to where your manage.py file is located. For example:
cd path/to/your/django/project

3. Run the Django Development Server

Once you're in the correct directory and the virtual environment is activated, run the following command to start the Django development server:

python manage.py runserver
This will start the Django server on the default address (http://127.0.0.1:8000/).

4. Confirm Server is Running
You should see something like this in your terminal:

Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
You can now open your browser and navigate to http://127.0.0.1:8000/ to see your Django application in action.
