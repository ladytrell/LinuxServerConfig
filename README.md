# Linux Server Configuration

- IP:  	34.235.63.160
- SSH Port:  	2200
- App URL 34.235.63.160/catalog

### Installed software

- psycopg2
- psycopg2-binary
- python
- apache2
- postgresql
- libapache2-mod-wsgi


### Configuration

https://github.com/ladytrell/LinuxServerConfig

1. Created user grader
2. Configured ssh to port 2200
3. Configured ufw
4. Installed and configured Apache2
5. Config WSGI for python app
6. Installed and configured PostgreSQL



### App Location

1.	/usr/local/www/catalog/
	a.	catalog.db
	b.	catalog.wsgi
	c.	lotofitems.py
	d.	catalogDB_Model.py
	e.	client_secrets.google.json
	f.	catalogDB_Model.pyc
	g.	fb_client_secrets.json 
	h.	catalog.py
	i.	static
		i.	responsive.css
		ii.	styles.css
	j.	templates
		i.	catalog.html
		ii.	item.html
		v.	category.html
2.	/etc/apache2/sites-available/
	a.	000-default.conf



### Referenced Sites

https://modwsgi.readthedocs.io/en/develop/configuration-directives/WSGIScriptAlias.html
https://modwsgi.readthedocs.io/en/develop/user-guides/quick-configuration-guide.html
http://flask.pocoo.org/docs/1.0/deploying/mod_wsgi/
https://realpython.com/flask-by-example-part-2-postgres-sqlalchemy-and-alembic/
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
https://docs.sqlalchemy.org/en/latest/core/connections.html
https://www.postgresql.org/docs/9.5/database-roles.html
https://overiq.com/sqlalchemy-101/installing-sqlalchemy-and-connecting-to-database/
https://tutorials.ubuntu.com/tutorial/install-and-configure-apache#2


License
----

MIT


**Free Software**
