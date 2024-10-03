1. Open the Project in VS Code
Launch VS Code.
Use File > Open Folder... to navigate to your project directory (FakeStatements) and open it.
2. Set Up the Python Environment
If you haven't already, make sure you have Python installed on your system.
Open the terminal in VS Code by selecting Terminal > New Terminal or using the shortcut Ctrl + `.
Create a virtual environment (if needed):
python -m venv venv
Activate the virtual environment:
On macOS/Linux:
source venv/bin/activate
On Windows:
venv\Scripts\activate
3. Install Dependencies
Ensure you have all the necessary packages installed (e.g., Django):
pip install django
Install mysqlclient: Use the following command to install the mysqlclient package:
pip install mysqlclient
If you encounter any issues during the installation, you might need to install some dependencies. On macOS, you can install the required libraries using Homebrew:
brew install mysql
brew install openssl
5. Run Database Migrations
If you are using Django and need to set up the database, run:
python manage.py migrate
