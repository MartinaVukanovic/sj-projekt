## Django Todo List


- Create a virtual environment in a `venv/` folder by typing `python -m venv venv` in your console.
- Activate the venv using `source venv/bin/activate` (Linux, MacOS) or `venv\Scripts\activate.bat` (Windows).
- Install the dependencies with `python -m pip install -r requirements.txt`
- Generate the empty SQLite database and tables using `python manage.py migrate`
- Run the app with `python manage.py runserver`
- Browse to the [app home page](http://localhost:8000/) to see the list of todo lists, which will initially be empty. 

You can now start using the UI to add your to-do lists and to-do items to the database. The data will be stored in a new `db.sqlite3` file in the root of your project directory.

You can also use Django's auto-generated admin interface at `http://localhost:8000/admin/` to view, add, and edit the data.
