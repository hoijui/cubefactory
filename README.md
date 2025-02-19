# CubeFactory 2

The CubeFactory 2 is an autonomous and portable mini factory with own energy and material supply. It embeds three modules: a 3D-printer, a plastic recycler producing filament for the 3D-printer for closed-loop material supply as well as photovoltaic panels and batteries for energy supply. It was developed at the [Department for Assembly Technology and Factory Management of the Technische Universität Berlin](http://www.mf.tu-berlin.de/) in the frame of the [Collaborative Research Center 1026 "Sustainable Manufacturing - Shaping Global Value Creation"](http://www.sustainable-manufacturing.net).

Key figures:
* Weight:
* Dimensions: 801 x 399 x 522 mm
* Autonomy: 8 hours of printing without power supply


In this repository, you will find the complete technical documentation produced in the development of the CubeFactory 2.

## Table of contents

* [About](#about)
* [Components](#components)
* [Contribute](#contribute)
* [License](#license)
* [More information](#more-information)

## About

![bild cf2](https://user-images.githubusercontent.com/28983580/27388247-3f9d4b84-569b-11e7-93f6-8e0f641c0413.jpg)

Especially in Emerging Countries there is a high demand for self-driven value creation. This is caused by an insufficient infrastructure of energy, technology and raw material. Also industrial and humanitarian supply chains are slow, difficult and expensive and equipment for value creation can be expensive and demands skills.
The motivation is that communities affected by a low standard of living or disaster are able to control their situation by manufacturing essential life-saving and life-sustaining supplies by their own.

In general, the CubeFactory 2 has the following purposes:
* Mediation of a sustain value creation
* Production of 3D printed objects by operating with disposable resources to create a sustain product
* Realization of closed loop material cycles
* Low-cost manufacturing of material and product
* Enabling small producers to access markets

## Components

The CubeFactory 2 contains all necessary infrastructure for production. It consists of the following components:
* 3D FDM printer
* Case
* Power supply, consisting of foldable solar panels and accumulator
* Recycler, consisting of PET shredder and extruder

![bild cf2 detail](https://user-images.githubusercontent.com/28983580/27388276-5469657a-569b-11e7-8936-568ee5e50a62.png)

### Cost overview

| Component | Cost in € | Details |
|:----| ----: | :---- |
| 3D-printer | 614 | [printer readme](3d_printer) |
| Case | 250 | [case readme](case) |
| Power supply | 4430<sup>1</sup> | [power supply readme](power_supply) |
| Recycler | 1200<sup>2</sup> | [recycler BOM](recycler/BOM_WeCycler.ods) |
| **Sum** | **6494** ||

**Notes on costs:**  
1: The cost for the power supply is that high because its parts were custom made to fit into the case. Alternative solutions for the power supply such as a plug could significantly reduce the cost to a few hundred Euros.  
2: The prices for the parts of the recycler have not been completely documented yet. Therefore, the above cost for the recycler is estimated.

## Contribute

Feel free to build and futher develop the CubeFactory 2. Any improvements of the work documented here are welcome.
There is a high flexibility in terms of selecting the particular components for the CubeFactory 2. For example, the power could alternatively be sourced from a car battery or generated through wind, water or nuclear fusion. While the 3D-printer is an independent open source project, the Recycler is an own development for the use in the CubeFactory and offers a lot of room for improvement.  

## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

## More information
* About the previous version of the CubeFactory as well as related projects such as the RecyclerBin: visit the [Cubefactory blog](http://cubefactory.org/).
* About the underlying concept: see the publication ["Realization of a Learning Environment to Promote Sustainable Value Creation in Areas with Insufficient Infrastructure"](http://www.sciencedirect.com/science/article/pii/S2212827115005399) (CC BY-NC-ND 4.0)
* About the results of the Collaborative Research Center "Sustainable Manufacturing - Shaping Global Value Creation": check the book ["Sustainable Manufacturing - Challenges, Solutions and Implementation Perspectives"](https://link.springer.com/book/10.1007/978-3-319-48514-0) (CC BY 4.0)
