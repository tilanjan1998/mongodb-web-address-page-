
install Mongodb
install Mongodb compass 
then in vs code 
npm install
npm start


**Create collection(table) named "users"**

```
> db.users.insert({name:"Tilanjan ray", age:22, email:"tilanjanray@gmail.com"})

```

**Query collection**

```
> db.users.find().pretty()
{
	"_id" : ObjectId("5acad2bc9cf54e14bc589de9"),
	"name" : "Tilanjan ray",
	"age" : 22,
	"email" : "tilanjanray@gmail.com"
}

