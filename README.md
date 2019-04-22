Clone the repository.

    $ git clone https://github.com/jonfung/ee225e_final_project.git
If you do not have a virtualenv, create a virtualenv.

    $ python3 -m venv env
Activate it.

    $ source env/bin/activate
Install requirements.

    $ pip install -r requirements.txt
Use ipython notebook as normal.

When you are making new ipython notebooks, make sure the new notebook uses `env` as the kernel.

When installing new dependancies through virtualenv, upload to git by updating the `requirements.txt` file.

    $ pip freeze > requirements.txt

