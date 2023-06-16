## Setup

1. If you don’t have Python installed, [install it from here](https://www.python.org/downloads/).

1. Navigate into the project directory:

   ```bash
   $ cd openai-quickstart-python
   ```

1. Create a new virtual environment:

   ```bash
   $ python -m venv venv
   $ . venv/bin/activate
   ```

1. Install the requirements:

   ```bash
   $ pip install -r requirements.txt
   ```

1. Make a copy of the example environment variables file:

   ```bash
   $ cp .env.example .env
   ```

1. Add your [API key](https://beta.openai.com/account/api-keys) to the newly created `.env` file.