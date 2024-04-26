# I verify that I am the sole author of the programs contained in this folder, except where explicitly stated to the contrary. 
# Signed: Ahmed Kafi - K21073085
# Date: 10/04/2024


# This file contains an overview of the project, showing users how it is run on the developers laptop.

1. Creating a Virtual Environment

Upon cloning the repository and accessing the project directory in the terminal, a virtual environment must be created using this command:

python3 -m venv env

To activate the virtual environment:

source env/bin/activate

2. Once virtual environment is active, requirements must me downloaded using the terminal:

pip install -r requirements.txt

3. The program is then run using the command:

python3 run.py 

4. While the program is run, the ngrok domain must also be run using the command terminal and running:

--domain=multiply-fond-possum.ngrok-free.app 8000

5. Once both are running simultaneously, the chatbot is ready to be used used on Whatsapp. 

Youtube walkthrough: https://youtu.be/6E-gn_vgQJA
