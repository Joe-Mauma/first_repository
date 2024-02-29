How to REQUEST and RECIEVE data

To able to request data, the client must utilize the communication pipeline ZEROMQ and connect to localhost:5555. 

Through this pipeline, a connection will be established between the two programs, and the client will be able to request/send data to the server and vice versa. 

The client will send string values to the server, with different values signifiying different requests. If the client sends an "ADD" string followed by a string ID (a numerical value stored as a string), the server will store and save the string ID. If the client sends a "REMOVE" string followed by a string ID (or not), the server will ignore the string ID. Finally, if the client sends just a "VIEW" string, then the server will retrieve the stored data of string IDs and return them to the client. 


![UML Diagram](https://github.com/Joe-Mauma/first_repository/assets/157445583/1b05b31f-c9d4-4d2d-b2db-a4e855235079)
