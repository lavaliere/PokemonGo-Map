# **Example.py rebase underway, please look in [rewrite branch](https://github.com/AHAAAAAAA/PokemonGo-Map/tree/py-rewrite) for more info.** 
##** Please refrain from submitting pull requests at this time!**

<p align="center">
<img src="https://raw.githubusercontent.com/AHAAAAAAA/PokemonGo-Map/master/static/cover.png">
</p>

# PokemonGo Map

[![Build Status](https://travis-ci.org/AHAAAAAAA/PokemonGo-Map.svg?branch=master)](https://travis-ci.org/AHAAAAAAA/PokemonGo-Map) [![Coverage Status](https://coveralls.io/repos/github/AHAAAAAAA/PokemonGo-Map/badge.svg?branch=master)](https://coveralls.io/github/AHAAAAAAA/PokemonGo-Map?branch=master)

Live visualization of all the pokemon (with option to show gyms and pokestops) in your area. This is a proof of concept that we can load all the pokemon visible nearby given a location. Currently runs on a Flask server displaying a Google Maps with markers on it.

Building off [Mila432](https://github.com/Mila432/Pokemon_Go_API)'s PokemonGo API, [tejado's additions](https://github.com/tejado/pokemongo-api-demo), [leegao's additions](https://github.com/leegao/pokemongo-api-demo/tree/simulation) and [Flask-GoogleMaps](https://github.com/rochacbruno/Flask-GoogleMaps).

---
For instructions, please refer to [the wiki](https://github.com/AHAAAAAAA/PokemonGo-Map/wiki)
---
#Work
python example.py -a ptc -u user -p pass -l "37.369706, -121.922504" -st 10

#Home
python example.py -a ptc -u user -p pass -l "37.327683, -121.884674" -st 10

#Going Home
python example.py -a ptc -u user -p pass  -l "37.362900, -121.910960" -st 10

#Selma Olinder Park
python example.py -a ptc -u user -p pass -l "37.333824, -121.865705" -st 10

#Dratini Nest in Fremont 
python example.py -a ptc -u user -p pass  -l "37.56721, -122.01187" -st 10

#Porygon sighted in Sunnyvale
python example.py -a ptc -u user -p pass -l "37.38292, -122.02694" -st 10

#Gastly sighted in Sunnyvale
python example.py -a ptc -u user -p pass -l "37.40905, -122.01793" -st 10

#Charmander Nest 
python example.py -a ptc -u user -p pass  -l "37.276285, -121.803162" -st 10

#Overfelt Park - Machoke, Vulpiz, Electrabuzz
python example.py -a ptc -u user -p pass -l "37.363033, -121.854721" -st 10
