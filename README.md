# rev11-twilio

Serverless application to send messages coming through an MQTT topic to an SQL database.

This serverless app requires an SQL Hosted database with the following Parameters:

SERVER - Database location, via IP or FQN

PORT - Port on which the database is accessible.

DATABASE - Database name

DRIVER - Database driver, can be one of the following: 'mssql', 'mysql', 'pg', 'oracle', 'sqlite'

ACCOUNT - Name of an account that has read privileges to the database.

PASSWORD - The password for ACCOUNT above.

TABLE - The table to save the data to.

TOPIC - Topic on which MQTT messages are published.

Made with ❤️ by Revolution11. Available on the [AWS Serverless Application Repository](https://aws.amazon.com/serverless)