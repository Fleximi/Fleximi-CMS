Storage
=======

.. note::

    For now, the available Data Storage for Fleximi is MySql.


Modify Connection String from `appsettings.json <https://github.com/gerardvidamo/Fleximi/blob/dev/alpha-fixes/src/Fleximi.Web/appsettings.json>`_::

    {
        "Logging": {
            "LogLevel": {
            "Default": "Warning"
            }
        },
        "AllowedHosts": "*",

        "Data": {
            "Provider": "MySql" // Options: MsSqlServer, MySql, SqlLite, PostgreSql
        },
        "DataOptions": {
            "MsSqlServerConnectionString": "Server=(localdb)\\mssqllocaldb;Database=fleximi;Trusted_Connection=True;MultipleActiveResultSets=true",
            "MySqlConnectionString": "server=localhost;userid=root;password=12345678;database=fleximi;"
        }
    }

MySql Server
------------

Using `MySql Server <https://dev.mysql.com/downloads/mysql/>`_, run this code to update database storage::

    sh ./scripts/development.sh --update-mysql

