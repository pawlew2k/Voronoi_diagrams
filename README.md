# Voronoi_diagrams

## Description

The program consists of two versions of the algorithm looking for Voronoi Diagrams for
a given set of points. The first is the implementation of the Fortune algorithm, the second is
the algorithm first uses Delaunay triangulation and then on the basis of this triangulation, it calculates
Voronoi diagram.

## Setup

To run this project, start all cells of the notebook consecutively.

Cells 1-3 are imports libraries and graphic tools. <br/>
Cell 4 is used to generate points. <br/>
Cell 5 contains implementations of the algorithm for finding a Voronoi diagram from triangulation Delaunay. <br/>
Cell 6 is for manual input of points. <br/>
Cell 7 is for selection points. You can either use the points you have entered yourself or generated. <br/>
Cell 8 is used to visualize the Fortune algorithm. <br/>
Cell 9 is used for library visualization of the function to find Voronoi diagram. <br/>
Cell 10 is visualization of an algorithm based on Delaunay triangulation. <br/>
Cell 11 is for generating graph of the operation times of individual algorithms. <br/>
Cell 12 is for saving points to the Json file. <br/>

Python files should be opened in a dedicated editor. You don't need this
to make the notebook work properly.

## Example
Our implementation shows next steps of the algorithm:
![obraz](https://user-images.githubusercontent.com/93039451/163727486-fdf48d90-1031-4272-8027-b04f2c236b49.png)
![obraz](https://user-images.githubusercontent.com/93039451/163727522-484dedb4-1600-41be-8596-a4afceb97f07.png)
![obraz](https://user-images.githubusercontent.com/93039451/163727543-24960db7-924a-4d7c-b718-1fe1fa9e066f.png)
![obraz](https://user-images.githubusercontent.com/93039451/163727586-abed79fa-e362-4010-99aa-ab4916860607.png)
![obraz](https://user-images.githubusercontent.com/93039451/163727592-04748c8e-a996-41ba-aa5b-926936f6be0b.png)
![obraz](https://user-images.githubusercontent.com/93039451/163727605-2d247fa9-e6ec-42c7-bf4a-c504f45632cb.png)
![obraz](https://user-images.githubusercontent.com/93039451/163727623-2b9f3ae6-38c6-4c90-994a-6bbfb7150c97.png)

Plot form scipy.spatial: Voronoi and voronoi_plot_2d:
![obraz](https://user-images.githubusercontent.com/93039451/163727655-00971133-381f-45df-848c-8f85e24c5c61.png)


## Authors
- Paweł Lewkowicz
- Mateusz Słuszniak
