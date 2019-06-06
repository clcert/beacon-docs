![](https://www.clcert.cl/assets/img/logo-clcert.svg)

# CLCERT Randomness Beacon Project

The **CLCERT Randomness Beacon** provides a public randomness service which is unpredictable, autonomous, consistent, and externally verifiable. The service emits a 512 bit-length random number at the beginning of each minute, retrieving entropy from different public sources.

The project itself is designed following a micro-services architecture, hence several different modules operate together in order to provide the service. Each of this modules is highly especialized and performs a concrete task inside the system.

Finally, the project is run using Docker containers in our production environment in order to facilitate the start, pause and update of the different modules without interefering in the rest of the system.

The CLCERT Randomness Beacon is the core service of [**Random UChile**](https://random.uchile.cl), which is a project that provides different randomness services using all the properties provided by the Randomness Beacon.

### Randomness Beacon Modules Repositories

* [Beacon Entropy Collector](https://www.github.com/clcert/beacon-collector)
* [Beacon Randomness Generator](https://www.github.com/clcert/beacon-record-generator)
* [Beacon Database Monitor](https://www.github.com/clcert/beacon-monitor)
* [Beacon API](https://www.github.com/clcert/beacon-api)
* [Beacon Verifier](https://www.github.com/clcert/beacon-verifier)
* [Beacon Docker Containers](https://www.github.com/clcert/beacon-docker)

### Development Wiki

In the [repository wiki](https://github.com/clcert/random-beacon/wiki) you will find details about the development of the project. Is focused on helping current and future developers of this project (or others similar) that wants 
to know about the architecture, security and troubleshooting of our project.

### Architecture

In the `architecture/` folder there are several diagrams showing the architecture of the service in different stages of the project.

### Algorithm

In the `algorithm/` folder there are images describing the algorithm used to generate the randomness output.
