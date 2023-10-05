# Goli Welcome On board App. - Docker.

Simple welcome on board app prepared as a support to safety induction for new joiners on board a vessel. 

**Docker Version includes:**
- Preconfigured `MariaDB` with imported initial [GoliShip SQL](https://github.com/devgitt82/GoliShip-SQL) database dump file
- `HTTPd` with [GoliShip React client](https://github.com/devgitt82/GoliShip-React) (static build files)
- `Java 17`
- [GoliShip API resource server](https://github.com/devgitt82/GoliShip-SpringBoot) - `jar` file

**Requirements:**
---

1. [Docker](https://docs.docker.com/get-docker/) 
   
**Installation and running:**
---

1. Clone repo to your local host.
2. Run `docker compose up` command.
3. Type `localhost:3000` on your web browser.

**Application login details for ordinary and admin users (OKTA authorization):**
---

1. login: `testuser@email.com`<br>
   password: `Biznes!@#!@#`

2. login: `adminuser@email.com`<br>
   password: `Biznes!@#!@#`
   

