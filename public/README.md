Lineage
========================

Lineage is build with [Phovea](http://phovea.caleydo.org).

Public Installation
-------------------

Lineage is publicly available at https://lineage.caleydoapp.org

Local Installation
------------------

Phovea uses Docker images to deploy and distribute its applications. In order to locally test Lineage, you need both
[Docker](https://docs.docker.com/engine/getstarted/step_one/) and [Docker-Compose](https://docs.docker.com/compose/install/) installed on your system.

To launch Lineage, download [the `docker-compose.yml`](https://raw.githubusercontent.com/Caleydo/lineage_product/latest/public/docker-compose.yml) file contained in this directory and execute:

```
docker-compose up
```

This will fetch the published state of the docker images and launch the system locally. Afterwards, open your web-browser and navigate to [http://localhost:8080](http://localhost:8080) to access the application.

To stop Lineage, hit `Ctrl+C` or execute the following command:

```
docker-compose stop
```

Source Code
------------------
The main repository for Lineage is at https://github.com/caleydo/lineage

***

<a href="https://caleydo.org"><img src="http://caleydo.org/assets/images/logos/caleydo.svg" align="left" width="200px" hspace="10" vspace="6"></a>
This project is part of **[Phovea](http://phovea.caleydo.org/)**, a platform for developing web-based visualization applications. For tutorials, API docs, and more information about the build and deployment process, see the [documentation page](http://phovea.caleydo.org).
