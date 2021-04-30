# Installation
````shell
mvn clean package
mv target/*.jars $PRESTO_HOME/plugin/phoenix
$PRESTO_HOME/bin/launcher restart
````
# Usage
```sql
select * from phoenix.db.name limit 10 ;
```