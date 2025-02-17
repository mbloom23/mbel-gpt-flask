# MBEL - Mini-Books for Entertainment and Learning

MBEL ("Mabel") is a picture book generator app based on the OpenAI API [quickstart tutorial](https://beta.openai.com/docs/quickstart). It uses the [Flask](https://flask.palletsprojects.com/en/2.0.x/) web framework. Follow the instructions below to setup the app.

## Setup

1. If you don’t have Python installed, [install it from here](https://www.python.org/downloads/).

2. Clone this repository.
   
   ```bash 
   git clone https://github.com/mbloom23/mbel-gpt-flask.git
   ```

3. Navigate into the project directory:

   ```bash
   cd mbel-gpt-flask
   ```

4. Create and activate a new virtual environment:

   ```bash
   python -m venv venv
   . venv/bin/activate # Mac
   # for Windows
   venv\Scripts\activate
   ```

5. Install the requirements:

   ```bash
   pip install -r requirements.txt
   ```

6. Make a copy of the example environment variables file:

   ```bash
   cp .env.example .env
   # for Windows
   copy .env.example .env
   ```

7. Add your [API key](https://beta.openai.com/account/api-keys) to the newly created `.env` file.

   ```bash
   export OPENAI_API_KEY='YOUR_API_KEY_HERE'
   ```
   Note: you may need to deactivate and reactivate your virtual environment here before running the app.

8. Run the app:

   ```bash
   flask run
   ```

You should now be able to access the app at the URL displayed in your terminal! Enter a topic or premise for your story in the box, press enter, and wait for the generation to load. Try describing different plot points, characters, or morals for your story.

<img width="1380" alt="Screen Shot 2023-03-18 at 6 21 27 PM" src="https://user-images.githubusercontent.com/89790185/226143378-1af19085-7803-4254-9ece-b3c811e5588b.png">
