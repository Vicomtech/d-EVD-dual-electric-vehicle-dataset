# d-EVD_dual-Electric-Vehicle-Dataset
This is a dual dataset of electric vehicle trips where battery, driving conditions and external conditions data is obtained. Electric car owners have the uncertainty of the battery range. Battery, speed, geo-position, traffic and weather parameters have a big influence in battery consumption. The purpose of these datasets is to train models for an accurate battery range prediction. 

It is a dual dataset because there are two different datasets. One is formed with synthetic data from a wide range of simulations (DEVST), and the other are real trips carried out with two different vehicles (DEVRT).

In the next sections, the content and the way to access to the datasets is explained.


## DEVST (Dataset of Electric Vehicle Synthetic Trips)

Simulations have been done using SUMO (Simulation of Urban MObility) software. Data consists of 21 different routes and for each route, 5 cars, 3 driving styles, 3 confort cases, 5 occupancy cases, 3 wind cases and 3 traffic situations have been combined. The cases are the following:

* Driving style: agressive, moderate, defensive.
* Confort: high, medium, low.
* Occupancy: 1, 2, 3, 4, 5.
* Traffic: high, medium, low.
* Wind: high, medium, low.

This combination gives a total of 42525 trips.

To gain access to the dataset, please fill the form in the following [link](https://www.google.es).

To know more about the process of getting data and building the dataset, refer to the following [paper](https://www.google.es).

## DEVRT (Dataset of Electric Vehicle Real Trips)

For the real trips dataset, many routes have been done, some more than one time, with two electric vehciles. A Dacia Spring and a Nissan Leaf. One is more intended to be used use in urban trips and the other in medium and large trips. For obtaining vehicle battery data, a OBD-II device has been used. For obtaining the rest of the data, two external apis have been used: 
* [Weatherapi](https://www.weatherapi.com/) for weather data.
* [Open data euskadi](https://opendata.euskadi.eus/) for traffic data.

As a result, during 5 consecutive days 29 urban/non-urban trips have been carried out with each vehicle, which gives a total of 58 trips.


To gain access to the dataset, please fill the form in the following [link](https://www.google.es).

<!--To know more about the process of getting data and building the dataset, refer to the following [paper](https://www.google.es). -->

## License
For both datasets:

Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0).

This license requires that reusers give credit to the creator. It allows reusers to distribute, remix, adapt, and build upon the material in any medium or format, for noncommercial purposes only. If others modify or adapt the material, they must license the modified material under identical terms.

## Contact

If you have any question or suggestion, do not hesitate to contact us at the following addresses:

* Eider Irigoyen: eirigoyen@vicomtech.org
* Iñaki Cejudo: icejudo@vicomtech.org
* Harbil Arregui: harregui@vicomtech.org
* Estíbaliz Loyo: eloyo@vicomtech.org 
