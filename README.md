# Keycloak with Spring Boot simple example

## Installation
In "run" folder
- $ bash install.sh
- $ bash run.sh

Open the Keycloak Admin : http://localhost:8180/auth/admin/
- create a Realm called franz
- create a client called springboot-keycloak (Client type = OpenID Connect)
- create a role (Realm roles >> create role)
- create an user with this role. Create a password in the Credentials Tab.

Clone this repo and run the app.
