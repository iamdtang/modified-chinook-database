This repository contains a modified version of the `chinook` SQLite database at https://www.sqlitetutorial.net/sqlite-sample-database/.

`chinook.db` is the `chinook` SQLite database but with all of the columns renamed to match Laravel conventions.

`chinook-postgres.sql` is a SQL dump of the `chinook.db` SQLite database after I manually migrated it to Postgres from SQLite. 

### ITP 405 Students

To import the `chinook-postgres.sql` SQL dump into your database using TablePlus:

1. Download `chinook-postgres.sql`
2. Open your database with TablePlus
3. `File` > `Import` > `From SQL Dump...` > Select the file and click `Open` > click `Import`
