`Database.Execute(SQLstatement [, parameters])`
Executes SQLstatement (with optional parameters) such as INSERT, DELETE, or UPDATE and returns a count of affected records.

`Database.GetLastInsertId()`
Returns the identity column from the most recently inserted row.
  
`Database.Open(filename)` or `Database.Open(connectionStringName)`
Opens either the specified database file or the database specified using a named connection string from the Web.config file.

`Database.OpenConnectionString(connectionString)`
Opens a database using the connection string. (This contrasts with Database.Open, which uses a connection string name.)

`Database.Query(SQLstatement[, parameters])`
Queries the database using SQLstatement (optionally passing parameters) and returns the results as a collection.

`Database.QuerySingle(SQLstatement [, parameters])`
Executes SQLstatement (with optional parameters) and returns a single record.

`Database.QueryValue(SQLstatement [, parameters])`
Executes SQLstatement (with optional parameters) and returns a single value.
