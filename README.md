# Improvement of [FIM UHK Navigation](https://github.com/r-bruha/Navigation)
## Improvement of existing algorithms (Nearest NeighBours & Particle Filters)
FIM UHK Navigation is currently implementing two most used algorithms for indoor localisation. I would like to adjust them in a way how they evaluate measured data from Wi-Fi, BlueTooth Low Energy and BTS due to previously recorded measurements in certain positions.

## Improvement of recording measurements
This part should help collectors evaluate likely accuracy of their measurements due to the previously recorded measurements which should help them identify potencionally wrong measurements in certain positions which could lead to wrong evaluation of results.

## Improvement of understanding how was position estimated
This part should help testers better understand how was position estimated which should help them identify where is a problem in cases of too much different estimated and real position.
