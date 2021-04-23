# opencartdocker

## Run this

sudo docker-compose up --build

## Create admin user through database

1. Open database
2. Find table oc_user
3. Insert new data directly or with SQL command

INSERT INTO oc_user VALUES (9999,1, 'admin123', '21232f297a57a5a743894a0e4a801fc3', '', 'firstname', 'lastname', ' email@example.com', '', '0.0.0.0',1,CURDATE());

This creates a new user with username: admin123 and password: admin.

Than you can enter into opencart admin section with those credentials.
