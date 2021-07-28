# The Tomorrow - CDL Quantum Hackathon 2021

## Project Description

*(3-4 lines about what it is and how you did it)*

## Setup

The project is managed by [conda](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html). Install all dependencies by running in the command line:

```{bash}
conda env create -f environment.yml
```

If you want to run in in Jupyter Notebook, see [How to set up Anaconda and Jupyter Notebook the right way](https://towardsdatascience.com/how-to-set-up-anaconda-and-jupyter-notebook-the-right-way-de3b7623ea4a).

TODO: explicit steps for DWave setup

## How to Use

*Example: From command line: Use python solvers/script.py -h*

## Challenge(s) You Solved

## Project Details

- Further walkthrough of what you did
- Links to any Jupyter notebooks/scripts

## Market opportunity
![Quantum CAD](https://github.com/stared/cdl-the-tomorrow/blob/main/images/Title.png)
### Urban Planning

We can find sprawls in every city. It is not necessarily about the population size or class stratifications, these "disconnected environments" emerge in every part of the world as a result of flawed urban planning.
Peter Calthorpe, a well-known architect and urban planner, points out that this phenomenon accounts for "not just environmental impacts, but our social well-being, the economic vitality, our sense of community and connectedness" [[1]](https://www.ted.com/talks/peter_calthorpe_7_principles_for_building_better_cities).  Billions of dollars are spent on traffic optimization, respiratory and heart diseases, carbon footprint reduction, land consumption optimization, residential segregation mitigation (just to name a few common issues). And those problems are still evolving. Right now, more than half of the world's population already live in cities, and another 2.5 billion people are projected to move to urban areas by 2050 [[2]](https://www.un.org/development/desa/en/news/population/2018-revision-of-world-urbanization-prospects.html). 

![Problems](https://github.com/stared/cdl-the-tomorrow/blob/main/images/Problems.jpg)

This, unfortunately, might lead to deplorable consequences:
> At the same time that we are solving for climate change, we are going to be building cities for three billion people. That is a doubling of the urban environment. If we do not get that right, I am not sure all the climate solutions in the world will save mankind.  
> 
> (c) Peter Calthorpe, TED lecture "7 principles for building better cities"  ([[1]](https://www.ted.com/talks/peter_calthorpe_7_principles_for_building_better_cities))

![Historical background](https://github.com/stared/cdl-the-tomorrow/blob/main/images/1_F5VRsKkQRzaBIxasDS-DNg.png)
<sup> from Stanislas Chaillou's "The Advent of Architectural AI, Historical Perspective" [3] </sup>

Urban planning and systematic architectural design as tools help to solve some of those issues. These methods have been developing for about a century now [[3]](https://towardsdatascience.com/the-advent-of-architectural-ai-706046960140). The conception of this design trend can be traced back to the early 1920s, to the modularity era. Walter Gropius, Le Corbusier [[4]](https://www.youtube.com/watch?v=5TEa7pZln_Q&ab_channel=MArch2UrbanUnit), they proposed modular grid and repetitive patterns in order to achieve technical simplicity and affordability to accommodate growing city populations. These trends have been adopted by many countries in different corners of the world from Eastern Europe and Asia to North and Latin America. However, zoning and clustering trends (many of which were adopted for good reasons, i.e. as the consequences of wars' disruptions and urbanization) have reinforced these sprawls which we are experiencing today [[5]](https://www.nationalgeographic.com/magazine/article/to-build-cities-of-the-future-stop-driving-cars). Furthermore, this LEGO-like conception of architecture has found criticism for the indifference to social expression and pre-existing cultural sites. And the homogeneity and complexity of structures started discouraging architects.

Then in the 50s, the advent of computation reestablished systematic design with an opportunity to realize scalable solutions and as a result, the first prototypes of CAD and CATIA emerged. Over the following decades, with growing computational power and storage capacities, 3D design software solutions became widely adopted. It led to the creation of Parametricism, "communicating certain commands to the computer while isolating key parameters impacting the result" [[3]](https://towardsdatascience.com/the-advent-of-architectural-ai-706046960140). With these tools, extraordinary architectural designs have been created (i.e. Zaha Hadid Architects' work [[6]](https://www.zaha-hadid.com/archive)).

However, there are several challenges associated with modern parametric design solutions.
> Parametric modelling failed to account for **(1) the compounded effect of multiple variables at once, (2) the imperative of space organization and style over strict efficiency, (3) the variability of scenarios**, and finally **(4) the computational cost of simulations.**
> 
> (c) Stanislas Chaillou, The Advent of Architectural AI, Historical Perspective ([[3]](https://towardsdatascience.com/the-advent-of-architectural-ai-706046960140))

In order to overcome these drawbacks, AI solutions were proposed [[7]](https://towardsdatascience.com/ai-architecture-f9d78c6958e0),  [[8]](https://arxiv.org/abs/2107.07397).  
This continuous progression from Modularity, to Computational Design, Parametricism and AI all leads us to the proposal of quantum-methods-based architectural optimization solutions. With the overall simplicity of the introduction of constraints (parameters), we believe the quantum approach will boost the computational power, mitigate certain computational errors and improve the overall design.

> For the most efficient and stable architectural and design solutions, we tend to copy nature as nature creates the ‘perfect’ patterns. Therefore, for creating the most suitable optimized solutions, we need to mimic nature and, hence, use quantum methods.

![Market](https://github.com/stared/cdl-the-tomorrow/blob/main/images/Market.jpg)

The above-mentioned reasons make the urban planning software and services market especially attractive. The overall market projection is estimated to reach ~US$ 211.4 billion by the end of 2027, with a rapid growth rate (CAGR of around 7% from 2019 to 2027) [[9]](https://www.prnewswire.com/news-releases/urban-planning-software--services-market-to-reach-us-211-4-bn-by-2027--initiatives-in-smart-city-developments-push-applications--a-new-report-by-transparency-market-research-301005843.html). The most prominent urban planning interest is expected to further develop in Asia, the Middle East, Africa and Latin America.

### Potential customers 

**Architectural software solutions**

- AutoDesk
- Rhino (especially, their Grasshopper 3D solution)
- CATIA 
- SketchUp 
- Revit

**Urban planning companies**

- Public sector
- Real Estate & Infra Companies
  * HDR (and their UrbanFootprint software)
  * Zaha Hadid Architects
  * SOM
  * WSP
  * ARUP
  * Populous



### Other business applications

![Other](https://github.com/stared/cdl-the-tomorrow/blob/main/images/Other.jpg)

- SAAS for interior and indoor designs, master plans creation
- Product design
- Engineering: circuit design optimization
- 3D computer graphics (e.g. game design)
- Board games design
- Fiber links, metros and power grid optimization (e.g. as a part of the urban design solutions)


### The Pitch
*(insert the link to the presentation)*


## Contributors

- Ravindra Babu - Data Scientist and Topological Data Analysis enthusiast, who is passionate about building impactful technological solutions to drive positive change
- Klem Jankiewicz - [Quantum Flytrap](https://quantumflytrap.com/)  - Designer who works in the intersection of STEMs and art, providing a creative approach to education and constantly challenging herself
- Piotr Migdał - [Quantum Flytrap](https://quantumflytrap.com/) - Quantum physicist, data vis specialist and AI consultant with unlimited curiosity and passion for science
- Victor Onofre - Quantum Engineer and a Quantum computing graduate, who wants to be on the frontlines of quantum technologies developments 
- Ekaterina Sokolovskaya - Quantum Nanoscience graduate and Entrepreneur who is driven by creating an added value by introducing high-tech solutions




