# Dremio to Dremio Connector


Can be used with

```
SELECT * FROM table(dremio.external_query('Select * from "SPACE".FOLDER.VDS'))
```

1. run mvn clean install
2. copy from ./target/dremio-dremioarp-plugin-19.1.0.jar to ../jars/
3. copy official Dremio's JDBC driver in ../jars/3rdparty
4. restart Dremio
