# Open-Source Simulation Cluster

![](./images/social_preview.png)

An open-source simulation cluster platform for running finite element analysis (FEA) and computational fluid dynamics (CFD) simulations.

## Services

The project is based on the following open-source software packages:

* [Code_Aster](https://code-aster.org/) - Finite element analysis
* [OpenFOAM](https://openfoam.org/) - Computational fluid dynamics
* [ParaView](https://www.paraview.org/) - Data visualization

## Sources

Part of the source code is written in [Python](https://www.python.org/) and uses the following libraries:

* [click](https://click.palletsprojects.com/en/stable/) - Command line interface library
* [asyncio](https://docs.python.org/3/library/asyncio.html) - Asynchronous programming library
* [aiohttp](https://docs.aiohttp.org/en/stable/) - Asynchronous HTTP client library
* [Flask](https://flask.palletsprojects.com/en/stable/) - HTTP server library
* [Flask-SocketIO](https://flask-socketio.readthedocs.io/en/latest/) - HTTP WebSocket library

Another part of the source code is written in [TypeScript](https://www.typescriptlang.org/) and uses the following libraries:

* TODO

## Commands

To start a cluster locally, run:

```
docker compose up
```

To stop the cluster, run:

```
docker compose down
```