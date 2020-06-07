# E-skeleton-Configurer


E-skeleton-Configurer is a docker project that will deploy in seconds a series of containers that will suite your needs.

In order to acces this Configurer Api the endpoint should be:
- http://Configurer:8888

You can search more of my E-skeletons docker projects and try to combine them in order to create a complete backend for your apps.
  - iOs_E-skeleton
  - Vue_E-skeleton
  - Api_E-skeleton

### Tech

E-skeleton-Configurer uses a number of open source projects to work properly:

* [node.js] - Evented I/O for the backend
* [Express] - Fast node.js network app framework 
* [MongoDB] - Classified as a NoSQL database program

### Installation

E-skeleton-Configurer requires [Docker](https://www.docker.com/) to run.

If you have Docker already installed in your pc, then proceed with this commands:

```sh
$ git clone https://github.com/headStyleColorRed/E-skeleton-Configurer.git
$ cd E-skeleton-Configurer
$ sh createEskeleton.sh
```

For personal environments you may want to change the 8th line in /server/app.js

```sh
$ Change => const dbLink = "mongodb://mongo:27017/mongotest"
$ For    => const dbLink = "mongodb://localhost:27017/mongotest"
```

### Todos

 - Add testing
 - Json web token auth

License
----

MIT


**Free Software, Hell Yeah!**%    