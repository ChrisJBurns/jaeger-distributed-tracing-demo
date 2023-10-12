# jaeger-distributed-tracing-demo
Parent project for Jaeger Distributed Tracing Demo

To initialise and pull all sub-modules, run the following:

```shell
git submodule update --init --remote --recursive
git submodule update --recursive
```

To build all projects run `docker-compose build`. Initially, the Java service will fail because you will need to build the jar. Once this has been built, you should be able to build all projects.

To run the demo, run `docker-compose up`.

To update the sub-modules to latest commits, run `git submodule update --remote`
