# cos-bucket

# create a virtualenv in .venv in the current directory
python3 -m virtualenv -p python3 .venv

# activate the virtualenv, you can deactivate with `deactivate` when done
. .venv/bin/activate

# install the project and all deps into the virtualenv
pip install -e .
