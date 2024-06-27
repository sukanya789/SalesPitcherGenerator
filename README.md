How to create and run the application:
 Step 1: 
 Create a Virtual Environment
 Open Terminal (or Command Prompt): Navigate to the directory where you want to create your FastAPI project and create a virtual environment.

Step 2: Install dependencies.
pip install google-generativeai
pip install langchain unstructured
pip install -U langchain-community 
pip install fastapi uvicorn

Step 3: Set Up Your Templates: 
                     Your application expects templates for rendering HTML responses (input_form.html and output.html). Ensure these templates are located in a directory named templates in the same directory where your Python script (main.py or any other name) resides.

Step 4: Write Your FastAPI Application: 
                  Create a Python file (e.g., main.py) where you define your FastAPI application and endpoints.

Step 5: Run the Application: 
In your terminal, with your virtual environment activated (venv), run the following command to start your FastAPI application.
                  uvicorn main:app

Once uvicorn starts the server, open a web browser and go to http://127.0.0.1:8000 (or another address and port if you specified different ones). You should see your input form (input_form.html). Fill in a URL and submit the form to generate and display the sales pitch and email content on output.html.
