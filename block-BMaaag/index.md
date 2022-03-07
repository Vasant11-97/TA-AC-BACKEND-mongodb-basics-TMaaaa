writeCode

Write code to:-

- create a database named `mountains`
<!-- use mountains -->
- a collection inside that database named `himalayas`
<!-- db.createCollection('himalayas') -->
- insert 1 document into that collection `{name: 'Dhauldhar range', height: '4000 mtrs'}`

<!-- 

    db.himalayas.insert({name: 'Dhauldhar range', height: '4000 mtrs'})

 -->

- insert multiple document using insertMany command

<!-- 

db.himalayas.insertMany([
{
name: 'Arravali Range',
height: '4000 meters'
},
{
name: 'Shivalik Range',
height: '5000 meters'
},
{
name: 'Kailash Range',
height: '8000 meters'
}
])

 -->

- find all documents from mountains

<!-- 

    db.himalayas.find()

 -->

- find a single document using name


<!-- db.himalayas.findOne({name: 'Dhauladhar range'}) -->


