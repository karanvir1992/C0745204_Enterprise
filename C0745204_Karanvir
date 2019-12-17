//Karanvir Singh (C0745204)


//Insert
const mongodb_client = require('mongodb').MongoClient;
let url = "mongodb+srv://c0742332:Guru@7428@cluster0-mwe55.mongodb.net/test?retryWrites=true&w=majority";
mongodb_client.connect(url, { useUnifiedTopology: true }, (err,conn)=>{
if (err) throw err;
console.log("Connected Successfully.");

let db = conn.db('Cars');

let col = db.collection('Kia');

var data=[{Model:"Sorento",Trim:"SUV",Year:2016,Color:"White",Price :47000,Transmission:"Manual"},
          {Model:"Optima",Trim:"Sedan",Year:2017,Color:"Black",Price :26800,Transmission:"Automatic"},
          {Model:"Rondo",Trim:"SUV",Year:2007,Color:"Grey",Price :27900,Transmission:"Automatic"}]

col.insertMany(data,(err,respond)=>{
if (err) throw err;
console.log("Data Inserted")
conn.close();
console.log("Connection Closed.")
});
});



const mongodb_client = require('mongodb').MongoClient;
let url = "mongodb+srv://c0742332:Guru@7428@cluster0-mwe55.mongodb.net/test?retryWrites=true&w=majority";
mongodb_client.connect(url, { useUnifiedTopology: true }, (err,conn)=>{
if (err) throw err;
console.log("Connected Successfully.");

let db = conn.db('Cars');

let col = db.collection('Range Rover');

var data=[{Model:"Discovery",Trim:"SUV",Year:2016,Color:"White",Price :117000,Transmission:"Manual"},
          {Model:"Velar",Trim:"SUV",Year:2017,Color:"Black",Price :126800,Transmission:"Automatic"},
          {Model:"Sport",Trim:"SUV",Year:2019,Color:"Green",Price :147900,Transmission:"Automatic"}]

col.insertMany(data,(err,respond)=>{
if (err) throw err;
console.log("Data Inserted")
conn.close();
console.log("Connection Closed.")
});
});


const mongodb_client = require('mongodb').MongoClient;
let url = "mongodb+srv://c0742332:Guru@7428@cluster0-mwe55.mongodb.net/test?retryWrites=true&w=majority";
mongodb_client.connect(url, { useUnifiedTopology: true }, (err,conn)=>{
if (err) throw err;
console.log("Connected Successfully.");

let db = conn.db('Cars');

let col = db.collection('Mazda');

var data=[{Model:"CX-3",Trim:"Coupe",Year:2014,Color:"Red",Price :33300,Transmission:"Manual"},
          {Model:"Mx-5",Trim:"Sedan",Year:2016,Color:"Black",Price :36800,Transmission:"Manual"},
          {Model:"Mazda3 Sport",Trim:"Sedan",Year:2018,Color:"White",Price :49900,Transmission:"Automatic"}]

col.insertMany(data,(err,respond)=>{
if (err) throw err;
console.log("Data Inserted")
conn.close();
console.log("Connection Closed.")
});
});



//Update
const mongodb_client = require('mongodb').MongoClient;
let url = "mongodb+srv://c0742332:Guru@7428@cluster0-mwe55.mongodb.net/test?retryWrites=true&w=majority";
// Connecting to mongodb
mongodb_client.connect(url, { useUnifiedTopology: true }, (err,conn)=>{
if (err) throw err;
console.log("Connected Successfully.");

let db = conn.db('Cars');

let col = db.collection('Kia');

var data= {Trim:"SUV"};

 var newvalues = { $set: {Price :35900} };

col.updateMany(data, newvalues,(err,respond)=>{
if (err) throw err;
console.log("Data updated")
//closing connection.
conn.close();
console.log("Connection Closed.")
});
});



//Delete
const mongodb_client = require('mongodb').MongoClient;
let url = "mongodb+srv://c0742332:Guru@7428@cluster0-mwe55.mongodb.net/test?retryWrites=true&w=majority";
// Connecting to mongodb
mongodb_client.connect(url, { useUnifiedTopology: true }, (err,conn)=>{
if (err) throw err;
console.log("Connected Successfully.");

let db = conn.db('Cars');

let col = db.collection('Mazda');

var myquery= {Transmission:"Manual"};


col.deleteMany(myquery,(err,respond)=>{
if (err) throw err;
console.log("Data deleted")
//closing connection.
conn.close();
console.log("Connection Closed.")
});
});



//Read
const mongodb_client = require('mongodb').MongoClient;
let url = "mongodb+srv://c0742332:Guru@7428@cluster0-mwe55.mongodb.net/test?retryWrites=true&w=majority";

mongodb_client.connect(url, { useUnifiedTopology: true }, (err,conn)=>{
if (err) throw err;
console.log("Connected Successfully.");

let db = conn.db('Cars');

let col = db.collection('Range Rover');

col.findOne({}, function(err, result){
if (err) throw err;
console.log(result)

conn.close();

});
});