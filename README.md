# db2_engine
Db2 engine for the IBM I


## Notes

When DB2 executes `CREATE PROCEDURE`, `CREATE TRIGGER`, or `CREATE FUNCTION`, it creates an ILE C Program `*PGM` or a service promgram `*SRVPMG` object. This is ILE C Code with embedded SQL.
