# python-virtual-environment
pip installation fails and venv required for installation

# Using a virtual environment: 

1. Install python3-venv (if it's not already installed):

sudo apt update
sudo apt install python3-venv

2. Create a virtual environment:

python3 -m venv myenv

3. Activate the virtual environment:

source myenv/bin/activate

4. Install the necessary package inside the virtual environment: Eg:

pip install python-ldap

5. Run your script while the virtual environment is activated:

./windapsearch.py --dc 10.10.10.4 -u 'test' -p 'test' --da

6. When you're done, you can deactivate the virtual environment by running:

deactivate
