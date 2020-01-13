---
title: Essential Algorithms and Data Structures
description: Introduces effective methodologies to develop complex 3D modeling algorithms using Grasshopper. It also covers extensively the data structure adopted by Grasshopper and its core organization and management tools.
authors: ['rajaa_issa']
sdk: ['General']
languages: ['C#', 'Python', 'VB']
platforms: ['Windows', 'Mac']
categories: ['General']
origin: unset
order: 2
keywords: ['rhino', 'developer']
layout: fullwidth-page
TODO: This needs to be shimmed for Mac Platform.
---

<div class="row">
<div class="col-10" markdown="1">   
# Essential Algorithms and Data Structures for Computational Design in Grasshopper First Edition


</div>
<div class="col-md-10 col-sm-12 col-sm-12" markdown="1">  

*Essential Algorithms and Data Structures for Computational Design* introduces effective methodologies to develop complex 3D modeling algorithms using Grasshopper. It also covers extensively the data structure adopted by Grasshopper and its core organization and management tools.

The material is directed towards designers who are interested in parametric design and have little or no background in programming. All concepts are explained visually using [Grasshopper® (GH)](www.grasshopper3d.com), the generative modeling environment for Rhinoceros® (Rhino). This book is not intended as a beginners guide to Grasshopper in terms of user interface or tools. Basic knowledge of the interface and workflow is assumed. For more resources and getting started guides, go to the learn section in [Rhinoceros® (Rhino)](www.rhino3d.com).

The content is divided into three chapters. [Chapter 1]({{ site.baseurl }}/guides/general/essential-mathematics/vector-mathematics/) discusses algorithms and data. It introduces a methodology to help create and manage parametric solutions. It also introduces basic data concepts such as data types, sources and common ways to process them. [Chapter 2]({{ site.baseurl }}/guides/general/essential-mathematics/matrices-transformations/) reviews basic data structures in Grasshopper. That includes single items and lists. [Chapter 3]({{ site.baseurl }}/guides/general/essential-mathematics/parametric-curves-surfaces/) includes an in-depth review of the tree data structure in Grasshopper and practical applications in design problems. All Grasshopper examples and tutorials are written with Rhinoceros version 6 and are included in the download.


![{{ site.baseurl }}/images/essential-algorithm-logo.png]({{ site.baseurl }}/images/essential-algorithm-logo.png){: width="100%"}

</div>  
</div>  

<div class="row">  
<div class="col-md-12" markdown="1">  

***[Rajaa Issa](https://discourse.mcneel.com/users/rajaa/activity)***

Robert McNeel & Associates

Download the <a href="{{ site.baseurl }}/files/math-samplesandtutorials.zip.zip"><span class="glyphicon glyphicon-download"></span></a> [math-samplesandtutorials.zip]({{ site.baseurl }}/files/math-samplesandtutorials.zip) archive, containing all the example Grasshopper and code files in this guide.

<a href="http://www.rhino3d.com/download/rhino/5.0/essentialmathematicsthirdedition/"><span class="glyphicon glyphicon-download"></span></a> [Download Essential Mathematics for Computational Design as a single PDF ](http://www.rhino3d.com/download/rhino/5.0/essentialmathematicsthirdedition/)

<a href="https://www.youtube.com/playlist?list=PLWIvZT_UEpWW6Kgq8mxOgliGBFHhrI4mK"><span class="glyphicon glyphicon-play"></span></a> [Watch the Essential Mathematics Videos... ](https://www.youtube.com/playlist?list=PLWIvZT_UEpWW6Kgq8mxOgliGBFHhrI4mK)

### Table of Contents  

</div>  
</div>  

<div class="row-fluid">  
<div class="col-md-4" markdown="1">  

### 1. [Algorithms and Data]({{ site.baseurl }}/guides/general/essential-algorithms/algorithms-and-data/)

   1.1 [Algorithmic design]({{ site.baseurl }}/guides/general/essential-algorithms/algorithms-and-data/#11-algorithmic-design)  
   
   1.2 [Algorithms parts]({{ site.baseurl }}/guides/general/essential-algorithms/algorithms-and-data/#12-algorithms-parts)  
   
   1.3 [Designing algorithms: the 4-step process]({{ site.baseurl }}/guides/general/essential-algorithms/algorithms-and-data/#13-designing-algorithms-4-step)  
   
   1.4 [Data]({{ site.baseurl }}/guides/general/essential-algorithms/algorithms-and-data/vector-mathematics/#14-data)  
   
   1.5 [Data Sources]({{ site.baseurl }}/guides/general/essential-algorithms/algorithms-and-data/#15-data-sources)  
   
   1.6 [Data Types]({{ site.baseurl }}/guides/general/essential-algorithms/algorithms-and-data/#16-data-types) 

   1.7 [Processing data]({{ site.baseurl }}/guides/general/essential-algorithms/algorithms-and-data/#17-processing-data)  
&nbsp;&nbsp; Numeric operations   
&nbsp;&nbsp; Logical operations    
&nbsp;&nbsp; Data analysis   
&nbsp;&nbsp; Sorting  
&nbsp;&nbsp; Selection   
&nbsp;&nbsp; Mapping    

   1.8 [Pitfalls of algorithmic design]({{ site.baseurl }}/guides/general/essential-algorithms/algorithms-and-data/#18-processing-data)  
&nbsp;&nbsp; Invalid or wrong type input   
&nbsp;&nbsp; Incorrect input    
&nbsp;&nbsp; Incorrect order of operation   
&nbsp;&nbsp; Long processing time  
&nbsp;&nbsp; Poor organization   

   1.9 [Algorithms tutorials]({{ site.baseurl }}/guides/general/essential-algorithms/algorithms-and-data/#19-algorithms-tutorials)  
&nbsp;&nbsp; Unioned circles tutorial   
&nbsp;&nbsp; Sphere with bounds tutorial    
&nbsp;&nbsp; Data operations tutorial   
&nbsp;&nbsp; Pitfalls tutorial  

</div>
<div class="col-md-4" markdown="1"> 

### 2. [Introduction to Data Structures]({{ site.baseurl }}/guides/general/essential-algorithms/data-structures/)
   2.1 [Overview]({{ site.baseurl }}/guides/general/essential-algorithms/data-structures/#21-overview)  

   2.2 [Generating lists]({{ site.baseurl }}/guides/general/essential-algorithms/data-structures/#22-generating-lists)  

   2.3 [List operations]({{ site.baseurl }}/guides/general/essential-algorithms/data-structures/#23-list-operations)  

   2.4 [List matching]({{ site.baseurl }}/guides/general/essential-algorithms/data-structures/#24-list-matching)  

   2.5 [Data structures tutorials]({{ site.baseurl }}/guides/general/essential-algorithms/data-structures/#25-data-structures-tutorials)  
&nbsp;&nbsp; Variable thickness pipe tutorial   
&nbsp;&nbsp; Custom matching tutorial  
&nbsp;&nbsp; Simple truss tutorial  
&nbsp;&nbsp; Pearl necklace tutorial    

</div>
<div class="col-md-4" markdown="1"> 


### 3. [Advanced Data Structures]({{ site.baseurl }}/guides/general/essential-algorithms/advanced-data-structures/)

   3.1 [The Grasshopper data structure]({{ site.baseurl }}/guides/general/essential-algorithms/advanced-data-structures/#31-the-grasshopper-data-structure)  
&nbsp;&nbsp; Introduction   
&nbsp;&nbsp; Processing data trees  
&nbsp;&nbsp; Data tree notation 

   3.2 [Generating trees]({{ site.baseurl }}/guides/general/essential-algorithms/advanced-data-structures/#32-generating-trees)  

   3.3 [Tree matching]({{ site.baseurl }}/guides/general/essential-algorithms/advanced-data-structures/#33-tree-matching)   

   3.4 [Traversing trees]({{ site.baseurl }}/guides/general/essential-algorithms/advanced-data-structures/#34-traversing-trees)   

   3.5 [Basic tree operations]({{ site.baseurl }}/guides/general/essential-algorithms/advanced-data-structures/#35-basic-tree-operations)   
&nbsp;&nbsp; Viewing the tree structure  
&nbsp;&nbsp; List operations on trees  
&nbsp;&nbsp; Grafting from lists to a trees  
&nbsp;&nbsp; Flattening from trees to lists
&nbsp;&nbsp; Combining data streams
&nbsp;&nbsp; Flipping the data structure
&nbsp;&nbsp; Simplifying the data structure     

   3.6 [Advanced tree operations ]({{ site.baseurl }}/guides/general/essential-algorithms/advanced-data-structures/#36-advanced-tree-operations)     
&nbsp;&nbsp; Relative items  
&nbsp;&nbsp; Split trees  
&nbsp;&nbsp; Path mapper  

   3.7 [Advanced data structures tutorials ]({{ site.baseurl }}/guides/general/essential-algorithms/advanced-data-structures/#37-advanced-data-structures-tutorials)     
&nbsp;&nbsp; Sloped roof tutorial  
&nbsp;&nbsp; Diagonal triangles tutorial  
&nbsp;&nbsp; Zigzag tutorial  
&nbsp;&nbsp; Weaving tutorial  

</div>
</div>
