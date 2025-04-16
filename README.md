# simple-python-app

Stop Writing Dockerfiles - Use Docker Init | Most Useful Docker Command
https://www.youtube.com/watch?v=Y5HQmgTNAtw&list=PLdpzxOOAlwvLjb0vTD9BXLOwwLD_GWCmC&index=10



Steps
git clone https://github.com/iam-veeramalla/python-for-devops.git
cd python-for-devops
cd simple-python-app

✅ Step-by-step: Use a Python virtual environment
1. Install python3-venv if it’s not already installed:

sudo apt update
sudo apt install python3-venv -y
2. Create a virtual environment inside your project directory:

python3 -m venv venv
3. Activate the virtual environment:

source venv/bin/activate
You should see (venv) appear at the start of your terminal prompt

4. Now install the requirements:
pip install -r requirements.txt
This will install flask and any other dependencies inside the virtual environment without touching system packages.

5. Run the app:

python app.py
6. In your browser, go to:

http://localhost:8000
