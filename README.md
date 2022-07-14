# Python Template

## Requirements

- On Debian/Ubuntu systems, you need to install the python3-venv
package using the following command: `apt-get install python3-venv`

## Usage 

Create [virtual environment](https://docs.python.org/3/tutorial/venv.html)(venv):

~~~~~
python3 -m venv venv
~~~~~

Enter venv:

~~~~
source venv/bin/activate
~~~~

Install dependencies:

~~~~~
pip3 install -r requirements.txt
~~~~~

Exit venv:

~~~~
deactivate
~~~~