# RASA - Echo Bot

## Bot Details
This Rasa bot is a simple echo bot. It echoes back whatever the user inputs. It's designed for basic interaction and demonstration purposes.

## Setup Environment

1. **Create and Activate Virtual Environment**: 
   - Create a new virtual environment by choosing a Python interpreter and making a `./venv` directory to hold it:
     ```bash
     python3 -m venv ./venv
     ```

   - Activate the virtual environment:
     ```bash
     source ./venv/bin/activate  # for Unix/macOS
     ```
     or
     ```bash
     .\venv\Scripts\activate  # for Windows
     ```

2. **Install Rasa**: 
   - Install Rasa Open Source within the virtual environment:
     ```bash
     pip install rasa
     ```

## Training the Bot

1. **Clone Repository**: 
   - Clone your Rasa bot repository:
     ```bash
     git clone https://github.com/mahaboobsabGoa/RASA-EchoBot.git
     ```

2. **Navigate to Repository**: 
   - Change directory to your bot repository:
     ```bash
     cd your_bot_repo
     ```

3. **Train the Bot**: 
   - Train the bot on the provided training data:
     ```bash
     rasa train
     ```

## Running the Bot

1. **Start Rasa Shell**: 
   - Start the Rasa shell to interact with the trained bot:
     ```bash
     rasa shell
     ```
