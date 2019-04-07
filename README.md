heroku-buildpack-snowflake-odbc
===

## Usage
This requires [heroku-buildpack-apt](https://github.com/heroku/heroku-buildpack-apt) to run before
it, with the following in the Aptfile:

```
unixodbc-dev
https://sfc-repo.snowflakecomputing.com/odbc/linux/2.18.3/snowflake-odbc-2.18.3.x86_64.deb
```
