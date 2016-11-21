Control Plane Services
======================

CPS provides an object-centric framework that mediates interactions between applications and allows user applications to interact with software components. The SONiC object library defines two types of application roles — clients and servers.

Client applications can execute create, set, get, and delete operations on individual objects or lists of objects. Server applications execute operations requested by client applications. Because client applications operate on objects, they do not need to be aware of the location or name of the server application that executes a requested operation.

CPS supports a publisher/subscriber model. Server applications publish relevant events — client applications can subscribe (register) for specific events and objects. Client applications can register for events generated when objects are created, modified, or deleted. The publisher/subscriber approach and object centric operations allow for the completely independent operation of client and server applications.
