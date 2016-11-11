qubmc_web README
==================

Requirements
------------
- python 3.5
- create a virtual environment in designated folder -> virtualenv venv
- goto venv/Scripts
- create project folder
- import project from git into this folder

Getting Started
---------------
- cd <directory containing this file>

- $VENV$/Scripts/<directory containing this file>/pip install -e .    <-- don't forget the period

- $VENV$/Scripts/<directory containing this file>/initialize_qubmc_web_db development.ini

- $VENV$/Scripts/<directory containing this file>/pserve development.ini

-------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------
OR (system wide pip installs)

- python 3.5
- create project folder
- import project from git into this folder
- <directory containing this file>/pip install -e .     <-- don't forget the period
- <directory containing this file>/initialize_qubmc_web_db development.ini
- <directory containing this file>/pserve development.ini

