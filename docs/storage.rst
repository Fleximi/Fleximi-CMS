Storage
=======

.. note::

    For now the available storage Data is MySql.


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

MySql
-----

Download `MySql Server <https://dev.mysql.com/downloads/mysql/>`_ and test the connection

