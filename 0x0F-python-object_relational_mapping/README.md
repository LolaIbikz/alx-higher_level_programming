0x0F Python - Object-relational mapping 🐍

Object-relational mapping is a programming technique for converting data between incompatible type systems using object-oriented programming languages. This creates, in effect, a "virtual object database" that can be used from within the programming language. This project covers relational mapping along SQL with Python.
At the end of this project, I was able to solve these questions:

How to connect to a MySQL database from a Python script
How to SELECT rows in a MySQL table from a Python script
How to INSERT rows in a MySQL table from a Python script
What ORM means
How to map a Python Class to a MySQL table
Tasks ✔️

Script that lists all states from the database hbtn_0e_0_usa
Script that lists all states from the database hbtn_0e_0_usa
Script that takes in an argument and displays all values in the states table of hbtn_0e_0_usa where name matches the argument.
Script that takes in arguments and displays all values in the states table of hbtn_0e_0_usa where name matches the argument. But this time, write one that is safe from MySQL injections!
Script that lists all cities from the database hbtn_0e_4_usa
Script that takes in the name of a state as an argument and lists all cities of that state, using the database hbtn_0e_4_usa
Python file that contains the class definition of a State and an instance Base = declarative_base()
Script that lists all State objects from the database hbtn_0e_6_usa
Script that prints the first State object from the database hbtn_0e_6_usa
Script that lists all State objects that contain the letter a from the database hbtn_0e_6_usa
Script that prints the State object with the name passed as argument from the database hbtn_0e_6_usa
Script that adds the State object “Louisiana” to the database hbtn_0e_6_usa
Script that changes the name of a State object from the database hbtn_0e_6_usa
Script that deletes all State objects with a name containing the letter a from the database hbtn_0e_6_usa
Python file similar to model_state.py named model_city.py that contains the class definition of a City.
Files model_city.py and model_state.py, and save them as relationship_city.py and relationship_state.py.
Script that lists all State objects, and corresponding City objects, contained in the database hbtn_0e_101_usa
Script that lists all City objects from the database hbtn_0e_101_usa
Results 📈

Filename				
0-select_states.py	1-filter_states.py	2-my_filter_states.py	3-my_safe_filter_states.py	4-cities_by_state.py
5-filter_cities.py	model_state.py	7-model_state_fetch_all.py	8-model_state_fetch_first.py	9-model_state_filter_a.py
10-model_state_my_get.py	11-model_state_insert.py	12-model_state_update_id_2.py	13-model_state_delete_a.py	14-model_city_fetch_by_state.py)
100-relationship_states_cities.py	relationship_city.py	relationship_state.py	101-relationship_states_cities_list.py	102-relationship_cities_states_list.py
Additional info 🚧

Resources

Python 3.5
PEP 8
MySQL 5.7
MySQLdb 1.3X
SQLAlchemy 1.2X
Try It On Your Machine 💻

git clone https://github.com/edward0rtiz/holbertonschool-higher_level_programming.git
cd 0x0F-python-object_relational_mapping
CONNECT TO A SQL SERVER (ONCE INSTALLED)
mysql -hlocalhost -uroot -p
TEST SCRIPT
cat FILENAME.sql | mysql -hlocalhost -uroot -p
FOR PYTHON SCRIPTS
