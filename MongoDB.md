### Connect to remote instance

    mongosh --host <host> --port <port>
    mongosh "mongodb://<host>:<port>" --username <user> --authenticationDatabase <db>

### Basic dump/restore

    mongodump --db <db> --collection <collection> --out <dir>
    mongorestore <dir>
