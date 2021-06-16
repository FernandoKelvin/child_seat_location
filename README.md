# Child Seat Localization

Author: Fernando Kelvin da Silva Soares

Notebook Versio: V0.0

## Introduction
In this project we will explore the child seat localization problem. The goal here, is to say in wich seat a child/infant seat is locates in the back part of a veicle. It was used as reference the SVIRO sunthetic dataset and some papers [1][2] wrote by the svriro team, available in [the SVIRO website](https://sviro.kl.dfki.de/), as weel as, other cientific papers and websites to implement a image classifier for each back seat position. 

Dififferently from the implementations presented by the SVIRO team on their papers, wich are focused on train the networks in one vehicle and see how they perform in unknown vhicles. In this work was decided to use more then one veichle for trainin and check the accuracy in unknown vehicles, to explore if there is a significant reseult compared to the single vehicle training.

The porpouse of this project is to give a flexible and fast framework to explore the child seat problem understanding the limitations and possibilities involved.

##### Copyright The SVIRO Authors

The usage of the SVIRO dataset is subjectet to the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. All all the credits must be given to the authors as follow.

[1] Steve Dias Da Cruz, Oliver Wasenmüller, Hans-Peter Beise, Thomas Stifter, & Didier Stricker (2020). SVIRO: Synthetic Vehicle Interior Rear Seat Occupancy Dataset and Benchmark. In IEEE Winter Conference on Applications of Computer Vision (WACV).

[2] Steve Dias Da Cruz, Bertram Taetz, Oliver Wasenmüller, Thomas Stifter, & Didier Stricker (2021). Autoencoder Based Inter-Vehicle Generalization for In-Cabin Occupant Classification. In IEEE Intelligent Vehicles Symposium (IV).
