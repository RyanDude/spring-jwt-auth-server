# spring-jwt-auth-server

#1 Once user login, the server will generate jwt and store it into redis. all other resource servers share the same redis server. if resource server receives a request with jwt header, it will judge if the tokens are in the redis. if yes, the user who send the request can access the resource server. The project still need a gateway and kubernate to become a small system. 
