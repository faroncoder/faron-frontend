faron-frontend
==============
node package orginially from:
Url: http://cwbuecheler.com/web/tutorials/2014/restful-web-app-node-express-mongodb/
GIT: https://github.com/cwbuecheler/node-tutorial-2-restful-app
----
Modified to my use

$npm install
$mongod --dbpath $PWD/data
$mongo
$use frontend
$db.userlist.insert({'username' : 'test1','email' : 'test1@test.com','fullname' : 'Bob Smith','age' : 27,'location' : 'San Francisco','gender' : 'Male'})
$exit

then node away!
