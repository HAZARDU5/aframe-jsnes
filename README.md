# aframe-jsnes
An experiment to run a javascript Nintendo emulator inside of virtual reality with a-frame


README from JSNES original repo ([https://github.com/bfirsh/jsnes](https://github.com/bfirsh/jsnes))


JSNES - A JavaScript NES emulator.
=====

Build
-----

To run locally:

    $ docker-compose up

And it'll be available at http://localhost

To build a distribution:

    $ docker-compose run build grunt

This will create ``jsnes.js`` and ``jsnes-min.js`` in ``build/``.

Benchmark
---------

The benchmark in ``test/benchmark.js`` is intended for testing JavaScript
engines. It does not depend on a DOM or Canvas element etc.
