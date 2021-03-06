#Deling, åpne data og API#

[![Greenkeeper badge](https://badges.greenkeeper.io/telemark/apps-tfk-deling.svg)](https://greenkeeper.io/)

Dette er nettstedet som omhandler Telemark fylkeskommunes åpne data, deling og API.

Siden kan sees på [http://apps.t-fk.no/api](http://apps.t-fk.no/api)

[![Build Status](https://travis-ci.org/telemark/apps-tfk-deling.png?branch=master)](https://travis-ci.org/telemark/apps-tfk-deling) [![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

##Slik setter du opp din egen kopi##

Nettsidene bruker [AngularJS](http://angularjs.org/), [Bootstrap](http://getbootstrap.com/) og er laget vha [Yeoman](http://yeoman.io/).

For å kunne sette opp egen kopi må du derfor ha installert [Node.js](http://nodejs.org/), [Yeoman](http://yeoman.io/) og [generator-angular](https://github.com/yeoman/generator-angular).

Når dette er på plass kan du klone repoet fra GitHub

```
$ git clone git@github.com:telemark/apps-tfk-deling.git
```

Gå inn i mappen som er lastet ned og hent nødvendige moduler vha npm og bower

```
$ npm install && bower install
```

For å starte lokal server bruker du grunt

```
$ grunt serve
```

Grunt brukes også til å kjøre testene

```
$ grunt test_dev
```

For å bygge løsningen for distribusjon er kommandoen enkelt og greit

```
$ grunt
```

Alle nødvendige filer pakkes, minimeres og kopieres til en mappe *dist* som du deretter kan servere fra fritt valgt webserver.
