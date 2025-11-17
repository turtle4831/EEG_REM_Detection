Haiii :3

to get the data set on your computer run this command to install uv on windows:
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
then
uv tool update git-annex
after git annex works us this command to install datalad
uv tool install datalad

on linux us: sudo apt-get install datalad

both os can then use datalad install https://github.com/OpenNeuroDatasets/ds005555.git to install the dataset

after that use this command to download the dependencies:
pip install -r requirements.txt
