# IPL-DATA-ANALYSIS
Indian Premier League 2008-2019

made-with-python GitHub license Ask Me Anything !

IPL-WallPaper

The Indian Premier League is a professional Twenty20 cricket league in India contested during March or April and May of every year by eight teams representing eight different cities in India. The league was founded by the Board of Control for Cricket in India in 2008.

Installation

Start by installing Python and Git if you have not already.

Next, clone this project by opening a terminal and typing the following commands (do not type the first $ signs on each line, they just indicate that these are terminal commands):

$ git clone https://github.com/bprasad26/ipl_data_analysis.git 
$ cd ipl_data_analysis

Next, create a virtual environment:

# create virtual environment
$ python3 -m venv ipl_venv
# Activate the virtual environment
$ source ipl_venv/bin/activate

Install the required packages

# install packages from requirements.txt file
$ pip install -r requirements.txt

Activate and Start jupyter Notebook

# activate venv for jupyter notebook
$ python -m ipykernel install --user --name=ipl_venv
# start jupyter notebook
$ jupyter notebook
# Note - at the top change the kernal to ipl_venv from the kernal dropdown if not done automatically.

deactivate the virtual environment, once done with your work

$ deactivate

to stay updated with this project

$ git pull
