writeCode

Write code to:-

- create a database named `sports`.

<!-- use sports -->

- list all databases present in local mongod server.

<!-- show dbs -->

- create 3 collections named `cricket`, `football`, `TT` in sports databse.

<!--

  db.createCollection('Cricket');
  db.createCollection('football');
  db.createCollection('TT');

 -->

- add multiple players in those collections which should have fields like `name`, `age` and `email` and `bid_price`.

<!--

  db.Cricket.insert({name: 'Vasant', age: 25, email: 'vasant.saraswat@gmail.com', bid_price: 30000000});

  db.Cricket.insert({name: 'Aditya', age: 25, email: 'ricky.goswami@gmail.com', bid_price: 30000000});

 -->

- list all collections in sports database.

<!-- show collections -->

- rename `TT` collection to `tennis`.

<!-- db.TT.renameCollection('Tennis') -->

- create a capped collection called `khokho` which should have max 3 documents.

<!--

db.createCollection( "khokho", { capped: true, size: 100000 } )

  db.khokho.insert({name: 'Vasant', age: 25})
  db.khokho.insert({name: 'Aditya', age: 28})
  db.khokho.insert({name: 'Zehan', age: 23})
 -->

Try inserting more than 3 and see what happens?

- check whether a collection is capped or not?

<!-- db.khokho.isCapped() -->

- drop all documents from `football` collection.

<!--  db.Football.remove({}); -->

- delete cricket collection completely.

<!-- > db.Cricket.drop();
 -->

- delete sports database.

<!-- db.dropDatabase() -->

- check which database you are connected to ?

<!-- sports -->

- connect to test database

<!-- use test -->
