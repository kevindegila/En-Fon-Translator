# EN-Fon-Translator

By [Kevin Degila](https://www.kevindegila.com/)
[TakwimuLab](https://takwimulab.gitlab.io/)

## Usage

Clone this repo

Create a Conda virtual environment if you have Anaconda or Miniconda installed
```sh
conda create -n translator python=3.6
```
Activate the environment:
```sh
conda activate translator
```
Install the required packages:
```sh
pip install -r requirements.txt
```
Download the model from this google drive folder and put it in the enfon_transformer folder:
https://drive.google.com/open?id=1PbrojtNSeZf8QpYmgJXtbcgYijVUU7Ay

And Execute this command to start making predictions
```sh
python3 -m joeynmt translate "config.yaml" 
```