<h1 align="center">
  <img src="https://raw.githubusercontent.com/ricsirigu/play26-swagger-reactivemongo/master/docs/logo.png" alt="logo">
   <br>
    Play Framework 2.6.x with Swagger and ReactiveMongo  
   <br>
  <h4 align="center">
A simple TODO app built with <a href="https://www.playframework.com/">play<a/>, <a href="https://github.com/swagger-api/swagger-play/tree/master/play-2.6/swagger-play">swagger<a/> and <a href="http://reactivemongo.org/">ReactiveMongo<a/>
  </h4>
</h1>


### How to run
You need
* MongoDB Installed and running on your machine with a database ```example```. Tutorial [here](https://docs.mongodb.com/v3.2/tutorial/install-mongodb-on-ubuntu/)
* SBT (mandatory if you don't want to use an IDE)
* IntelliJ to import the project (optional)
* SBT plugin (optional)

Tho ways to run the project:
* Import the project, run SBT and type ```run```  to launch the server.
* cd into the project directory, run SBT and type ```run```  to launch the server.

Then open your favourite browser and go to

```localhost:9000/api-docs```

From the beautiful Swagger-UI interface you can perform all the CRUD operations you want

Enjoy.

Author: [Riccardo Sirigu](https://www.riccardosirigu.com/)
