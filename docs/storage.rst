Storage
=======

.. note::

    For now the available storage Data is MySQL.

MySQL
-----

Download `MySQL Server <https://dev.mysql.com/downloads/mysql/>`_ and test connections

Modify Connection String from::

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

