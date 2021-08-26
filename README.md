# SqlAchemy Tutorials
These notebooks are mini tutorials demonstrating critical aspects of SqlAlchemy and Python

The tiles are pretty straight forward.  SqlAlchemy has 3 main modes:
- engine/execute
- ORM Declarative ( creating databases )
- ORM Reflection ( using existing databases )

Of course to understand ORM ( Object Relationship Model ) you have to know a little about Object Oriented Programming.  So OOP is pesented before ORM content to prepare you for using objects related to ORM.

SQLite is the database used and the example files are included.

The zip install of [DB BRowser](https://sqlitebrowser.org) is included for visual interaction with SQLite databases

Unzip the folder and create a shortcut to "DB Browser for SQLite.exe".  This is so you can view the database files.  Though it is strictly not necessary for the examples.

ORM can be awesome.  All you have to do is change the connect string in your [create_engine](https://docs.sqlalchemy.org/en/14/core/engines.html) and all your database code just works!
