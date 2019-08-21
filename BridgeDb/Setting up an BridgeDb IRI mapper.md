# Setting up an BridgeDb IRI mapper

This is a notebook of my steps of setting up a BriddgeDb IRI mapping service, but with
only the BridgeDb components, and thus not a full-fledged Open PHACTS IMS.

1. set up MySQL or MariaDB (tested with MariaDB 10.3)
2. choose sql username and password
3. update the username/pwd in these two files:
   1. mysqlConfig.sql
   1. BridgeDb source code: org.bridgedb.utils/resources/BridgeDB.properties
4. create users. Getting root access can be tricky. See mysqlConfig.sql
   Pural, bc it creates a regular account and a test account.
5. create tables. See mysqlConfig.sql

## Debian 10 notes

```shell
apt install mariadb-server tomcat8-admin
```
