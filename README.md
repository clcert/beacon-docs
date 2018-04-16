![](https://www.clcert.cl/img/logo-clcert.png)

# CLCERT Random Beacon Project

The [CLCERT Random Beacon Project](https://beacon.clcert.cl) provides a public randomness service which is unpredictable, autonomous, consistent, and externally verifiable.

The project itself is designed following a micro-services architecture, hence several different modules operate together in order to provide the service. Each of this modules is highly especialized and performs a concrete task inside the system.

Finally, the project is run using Docker containers in our production environment in order to facilitate the start, pause and update of the different modules without interefering in the rest of the system.

### Modules Repositories

* [Beacon Collector](https://www.github.com/clcert/beacon-collector)
* [Beacon Generator](https://www.github.com/clcert/beacon-record-generator)
* [Beacon Database Monitor](https://www.github.com/clcert/beacon-monitor)
* [Beacon API](https://www.github.com/clcert/beacon-api)
* [Beacon Frontend](https://www.github.com/clcert/beacon-frontend)
* [Beacon Verifier](https://www.github.com/clcert/beacon-verifier)
* [Beacon Docker](https://www.github.com/clcert/beacon-docker)


### Development Wiki

In the [repository wiki](https://github.com/clcert/random-beacon/wiki) you will find details about the development of the project. Is focused on helping current and future developers of this project (or others similar) that wants to know about the architecture, security and troubleshooting of our project.
