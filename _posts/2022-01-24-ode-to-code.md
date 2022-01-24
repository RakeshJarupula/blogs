---
title: "[Machine-Hack] Ode To Code: Predicting Weather Using Alien Fruit Properties - 6th Place Solution🚀"
layout: post
---

![Machine-Hack](/assets/images/ode_to_code.jpg)

Hi There👋, in this blog I will be sharing my **6th place solution**🏆 to a hackathon hosted at [Machine Hack](https://machinehack.com/) called [**Ode To Code: Predicting Weather Using Alien Fruit Properties**](https://machinehack.com/hackathon/odetocode_predicting_weather_using_alien_fruit_properties/overview)🍊🍋. 



Before starting let's look at the problem statement and the data set attributes.
## Problem statement:
The year is 2050 and a team of astronauts from all over the world went on a mission to an Exoplanet and discovered a vast amount of life and awesome weather. The scientists began collecting data samples of fruits found in their landing site and were curious by their shape and size. They collected data for more than a solar year of the planet to understand the fruit growing conditions in different weathers. 

To analyze data and grow fruits similar to earth, they began transmitting data back to the Earth, however, due to solar radiation, some data got corrupted and got lost in transmission. Back on Earth, the scientists figured they need to identify the type of climate the exoplanet has based on the properties of the fruit with the existing challenge of missing data. Help the scientists identify the earth-like season in which the fruit must have grown using the data collected.

## Data set attributes:
Independent Variables

    edible-poisonous: edible=e, poisonous=p
    cap-diameter: float number in cm
    cap-shape: bell=b, conical=c, convex=x, flat=f, sunken=s, spherical=p, others=o
    cap-color: brown=n, buff=b, gray=g, green=r, pink=p, purple=u, red=e, white=w, yellow=y, blue=l, orange=o, black=k
    does-bruise-bleed: bruises-or-bleeding=t,no=f
    gill-attachment: adnate=a, adnexed=x, decurrent=d, free=e, sinuate=s, pores=p, none=f
    gill-color: see cap-color + none=f
    stem-height: float number in cm
    stem-width: float number in mm
    stem-color: see cap-color + none=f
    has-ring: ring=t, none=f
    ring-type: cobwebby=c, evanescent=e, flaring=r, grooved=g, large=l, pendant=p, sheathing=s, zone=z, scaly=y, movable=m, none=f
    habitat: grasses=g, leaves=l, meadows=m, paths=p, heaths=h, urban=u, waste=w, woods=d

Dependent variable

    season: spring=s, summer=u, autumn=a, winter=w


# Let's see the code now.
<iframe src="https://www.kaggle.com/embed/jarupula/mh-ode-to-code-pred-weather-6th-place-sol?kernelSessionId=86050512" height="800" style="margin: 0 auto; width: 100%; max-width: 950px;" frameborder="0" scrolling="auto" title="[MH] Ode to Code: Pred Weather🍊 - 6th Place sol."></iframe>

Notebook: https://www.kaggle.com/jarupula/mh-ode-to-code-pred-weather-6th-place-sol 