# MNML Conky
![Preview](https://github.com/VaughnValle/demo/blob/master/preview.png)

## Description
A clean and simple [Conky](https://github.com/brndnmtthws/conky) theme derived from [Conky Vision](https://github.com/zagortenay333/conky-Vision)

This Conky theme shows the __time__, __date__, __current weather__, and __forecast__ for the next 4 days while keeping a minimal interface


## Dependencies
Depends on:
* __git__
* __conky__ ```1.10.x``` (build)
* __curl__ (build)
* __jq__ (build)
* __gawk__ (build)
* __[Conky Vision](https://github.com/zagortenay333/conky-Vision)__ (Conky theme)
* __[OpenWeatherMap](http://openweathermap.org)__ (weather forecast) 
* __[Poiret One](https://fonts.google.com/specimen/Poiret+One)__ (fonts)


## Installation Steps (Ubuntu 20.04)
1. Register an account on [OpenWeatherMap](http://openweathermap.org) to get a free private API key for weather forecasts
2. Find your City ID from OWM's [list](http://bulk.openweathermap.org/sample/city.list.json.gz) 
3. Update repositories with ```sudo apt update```
4. Install software dependencies with ```sudo apt install git conky-all curl jq gawk```
5. Install [Conky Vision](https://github.com/zagortenay333/conky-Vision), see __Installation__
   - Clone repo with ```git clone https://github.com/zagortenay333/conky-Vision.git```
   - Cd into dir with ```cd conky-Vision```
   - Run ```install``` script with ```./install``` (automatic) __or__
   - Move ```.conky-vision``` folder & ```.conkyrc``` file into your home ```~``` directory (manual)
