collection-extended-api
=======================

Package that extends the Collection API.

----------------------------
#### Collection

- drop()
- explain()
- lookup('test');
- serverStatus.workingSet
- stats.indexSize

````
// .explain()
db.serverStatus({workingSet:1}).workingSet  
db.stats().indexSize  

// .lookup('test')
var myTestCollection = Mongo.Collections.lookup('test');
````

----------------------------
#### ObjectID
- String() 
- getTimestamp() 


