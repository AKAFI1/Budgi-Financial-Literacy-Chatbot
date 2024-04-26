# I verify that I am the sole author of the programs contained in this folder, except where explicitly stated to the contrary. 
# Signed: Ahmed Kafi - K21073085
# Date: 10/04/2024

# Set up NGROK domain

1. If you're not an ngrok user yet, just sign up for ngrok for free.
2. Download the ngrok agent.
3. Go to the ngrok dashboard, click Your Authtoken, and copy your Authtoken.
4. Follow the instructions to authenticate your ngrok agent. You only have to do this once.
5. On the left menu, expand Cloud Edge and then click Domains.
6. On the Domains page, click + Create Domain or + New Domain. (here everyone can start with one free domain)


# This file contains an overview of the project, showing users how it is run on the developers laptop.

1. Creating a Virtual Environment

- Upon cloning the repository and accessing the project directory in the terminal, a virtual environment must be created using this command:

- python3 -m venv env

- To activate the virtual environment:

- source env/bin/activate

2. Once virtual environment is active, requirements must me downloaded using the terminal:

- pip install -r requirements.txt

3. Uncomment the env file and add your phone number to the "RECIPIENT_WAID" to connect the chatbot to your whatsapp.

4. The program is then run using the command:

- python3 run.py 

5. While the program is run, the ngrok domain must also be run using the command terminal and running:

- ngrok http 8000 --domain your-domain.ngrok-free.app

- ngrok will display a URL where your localhost application is exposed to the internet (copy this URL for use with Meta).

6. Once both are running simultaneously, the chatbot is ready to be used used on Whatsapp. 


Youtube walkthrough: https://youtu.be/6E-gn_vgQJA
