---
title: "Student project: Puzzle Solver"
description: ""
slug: "puzzlesolver"
#image: "/projects/bachelorthesis.jpg"
keywords: ""
categories: 
    - ""
    - ""
date: 2014-02-01T21:28:43-05:00
draft: false
---
For this student project we developed a puzzle solver. 
The input were some pictures with several, different pieces of the puzzle. 
The single pieces were extracted from the picture. 
With information about the geometric and color characterstics of the endges the coherent pieces were calculated.
With the calculated result the output of the puzzle solver was a 3D animation in which the random placed single puzzle pieces flew to their destination.
Finally a solved puzzle is shown on the monitor.
<br> To extract the single puzzle pieces, the geometric and color information was the task of my team. 
At first we used the Harris corner detection to find the corners of the pieces.
To find the four corners and distinguish the different pieces the vectors between the corners were checked by the dot product to be close to zero. The results are four points for each puzzle, creating a square
The geometric information was calculated by taking the middle of the vectors, moving along a line 90 degrees to the vector and check if there is puzzle fabric outside of the square, a lack of fabric within or none of them.
By moving along the edge in equidistance parts and evaluate the color we gained the color information.
We offered all these information in a XML document for further processing steps.

<div style="text-indent:20px;"><b>Trained Skills</b></div>
<div style="text-indent:20px;">- Programm language C++</div>
<div style="text-indent:20px;">- OpenCV for image processing</div>

