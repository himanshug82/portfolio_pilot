# portfolio_pilot
pip install virtualenv

python -m venv venv
source venv/bin/activate

pip install --upgrade pip
pip install pip-review

pip list

pip-review --local --interactive

pip-review --local --auto

pip freeze > requirements.txt

pip install -r requirements.txt

pip check

pip install --upgrade -r requirements.txt