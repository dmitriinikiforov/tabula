### Connect

    mysql --host=<host> --port=<port> --user <user> -p <db-name>

### Get info

    show databases;
    show tables;
    describe <table>;

### Add column

    alter table <table> add column <column_name> <type> [not null] [default <value>];
