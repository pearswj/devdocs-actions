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
<div class="col-12" markdown="1">   
# Essential Algorithms and Data Structures for Computational Design in Grasshopper First Edition


</div>
<div class="col-md-12 col-sm-12 col-sm-12" markdown="1">  

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

   2.2 [Generating lists]({{ site.baseurl }}/guides/general/essential-algorithms/data-structures/#22-generating-lists)  

   2.2 [Transformation operations]({{ site.baseurl }}/guides/general/essential-mathematics/matrices-transformations/#22-transformation-operations)  
&nbsp;&nbsp; Translation (move) transformation   
&nbsp;&nbsp; Rotation transformation  
&nbsp;&nbsp; Scale transformation  
&nbsp;&nbsp; Shear transformation  
&nbsp;&nbsp; Mirror or reflection transformation  
&nbsp;&nbsp; Planar Projection transformation  

</div>
<div class="col-md-4" markdown="1"> 


### 3. [Parametric Curves and Surfaces]({{ site.baseurl }}/guides/general/essential-mathematics/parametric-curves-surfaces/)

   3.1 [Parametric curve]({{ site.baseurl }}/guides/general/essential-mathematics/parametric-curves-surfaces/#31-parametric-curves)  
&nbsp;&nbsp; Curve parameter  
&nbsp;&nbsp; Curve domain or interval  
&nbsp;&nbsp; Curve evaluation  
&nbsp;&nbsp; Tangent vector to a curve  
&nbsp;&nbsp; Cubic polynomial curves  
&nbsp;&nbsp; Evaluating cubic Bézier curves  

   3.2 [NURBS curves]({{ site.baseurl }}/guides/general/essential-mathematics/parametric-curves-surfaces/#32-nurbs-curves)  
&nbsp;&nbsp; Degree  
&nbsp;&nbsp; Control points  
&nbsp;&nbsp; Weights of control points  
&nbsp;&nbsp; Knots  
&nbsp;&nbsp; Knots are parameter values  
&nbsp;&nbsp; Evaluation rule  
&nbsp;&nbsp; Characteristics of NURBS curves  
&nbsp;&nbsp; Evaluating NURBS curves  

   3.3 [Curve geometric continuity]({{ site.baseurl }}/guides/general/essential-mathematics/parametric-curves-surfaces/#33-curve-geometric-continuity)   

   3.4 [Curve curvature]({{ site.baseurl }}/guides/general/essential-mathematics/parametric-curves-surfaces/#34-curve-curvature)   

   3.5 [Parametric surfaces]({{ site.baseurl }}/guides/general/essential-mathematics/parametric-curves-surfaces/#35-parametric-surfaces)   
&nbsp;&nbsp; Surface parameters  
&nbsp;&nbsp; Surface domain  
&nbsp;&nbsp; Surface evaluation  
&nbsp;&nbsp; Tangent plane of a surface  

   3.6 [Surface geometric continuity]({{ site.baseurl }}/guides/general/essential-mathematics/parametric-curves-surfaces/#36-surface-geometric-continuity)     

   3.7 [Surface curvature]({{ site.baseurl }}/guides/general/essential-mathematics/parametric-curves-surfaces/#37-surface-curvature)     
&nbsp;&nbsp; Principal curvatures  
&nbsp;&nbsp; Gaussian curvature  
&nbsp;&nbsp; Mean curvature  

   3.8 [NURBS surfaces]({{ site.baseurl }}/guides/general/essential-mathematics/parametric-curves-surfaces/#38-nurbs-surfaces)     
&nbsp;&nbsp; Characteristics of NURBS surfaces  
&nbsp;&nbsp; Singularity in NURBS surfaces  
&nbsp;&nbsp; Trimmed NURBS surfaces  

   3.9 [Polysurfaces]({{ site.baseurl }}/guides/general/essential-mathematics/parametric-curves-surfaces/#39-polysurfaces)     

   3.10 [Tutorials]({{ site.baseurl }}/guides/general/essential-mathematics/parametric-curves-surfaces/#310-tutorials)     
&nbsp;&nbsp; Continuity between curves  
&nbsp;&nbsp; Surfaces with singularity  

</div>
</div>
