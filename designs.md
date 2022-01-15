# LigerCMS
# Design Docs

Liger CMS goal is to provide CMS / SaaS platform that can grow with a organizations needs. Liger will implement a microservice architecture and a seperated API (server) & GUI (client) apps. Liger shall be slim, fast, and fierce. 



## AUTH

Authentication Service will be provided by Auth microservice using JWT (JSON Web Tokens)
Auth services will verify Token and require below fields:

*JWT*: 
 - UID
 - User (username)
 - Domain (org)
 - First Name
 - Last Name
 - Avatar
 - Roles: []
 - Created: (datetime)
 - Expires: (datetime)
 - 

Group based permissions will be provided by another service. 


## GUI

* Page
  - Routes
  - Template
     * Blocks
  - Themes
      * Color Schemas





## API

* Page
  - Route
  - Blocks
  - 
