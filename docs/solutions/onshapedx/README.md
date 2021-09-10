---
layout: doc
title: Onshape Digital Twins
permalink: /docs/solutions/onshapedx
description: This page shares ways that Onshape can be used for more than traditional mechanical design. Most of this work uses the Onshape API Snippets Library in Google Colab or Jupyter Notebooks.
---

<div class="container"><h2>Digital Twins</h2>
PTC defines a <b>digital twin</b> as any digital representation of a physical thing -- this can be a ThingWorx dashboard, or an immersive Augmented Reality eperience that reflects the state of a physical artifact or process. <br /><br />  
This page shares ways that Onshape can be used for more than traditional mechanical design. Most of this work uses the <a href="https://colab.research.google.com/github/PTC-Education/PTC-API-Playground/blob/main/Onshape_API_Snippets.ipynb">Onshape API Snippets Library</a> in Google Colab or Jupyter Notebooks.
</div>
<div class="container">
            <p style="text-align:center"><img src="/docs/solutions/onshapedx/dxOnshapeMap.jpg" width="100%" alt="DX Onshape Technology Map" margin="300px 0px 100px 0px"/></p>
</div>
<h4>Click below to jump to a section of the framework</h4>
<p><ol>
<li><a href="#Connect">Connect</a></li>
<li><a href="#Analyze">Analyze</a></li>
<li><a href="#Monitor">Monitor</a></li>
<li><a href="#Control">Control</a></li>
<!-- <li><a href="#Automate">Automate</a></li>
<li><a href="#Optimize">Optimize</a></li>    -->
</ol></p>
<h3>Getting Started</h3>
<div class="container">
        <div class="columns is-vcentered is-centered is-multiline ">
            <div class="column is-one-half">
                <p style="text-align:center"><iframe width="100%" height="220" src="https://www.youtube.com/embed/LJ-vz1op80M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>
                <div class="subtitle" style="text-align:center">Onshape API Setup</div>
            </div>
            <div class="column is-one-half is-vcentered is-centered">
                <p style="text-align:center"><iframe width="100%" height="220" src="https://www.youtube.com/embed/LnLk_it8QoM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>
                <div class="subtitle" style="text-align:center">Edge Device Connectivity</div>
            </div>
        </div>
</div>
<br>
<a name="Connect"></a>
<div class="container"><h2>Connect</h2>
Once you've created app keys for Onshape and gotten started with the Python client, you can start making simple applications with pyhthon that use Onshape as a visualizer.
<br>
<br>
<table>
    <thead>
        <tr>
            <th width="200">Application</th>
            <th>Preview</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Onshape Countdown Timer - <a href="https://colab.research.google.com/github/PTC-Education/PTC-Education.github.io/blob/master/Onshape_Countdown_DX_in_Education_Summit.ipynb">click here to see notebook</a></td>
            <td style="text-align:center"><iframe width="350" height="220" src="https://www.youtube.com/embed/SsnQwAAqDRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
        </tr>
        <tr>
            <td>Transformation Matrix Lesson Plan - <a href="https://colab.research.google.com/github/PTC-Education/PTC-API-Playground/blob/main/Transformation_Matrices_Lesson_Plan.ipynb">click here to see notebook</a></td>
            <td style="text-align:center"><img src="/docs/solutions/onshapedx/transformationMatrixGif.gif" width="350" alt="Teaching Transformation Matrices"/></td>
        </tr>
    </tbody>
</table>
</div>
<br>

<a name="Analyze"></a>
<div class="container"><h2>Analyze</h2>
Once you can use python notebooks to create connected applications, you can use python to analyze complex, 3D systems and run simulations.
<br>
<br>
<table>
    <thead>
        <tr>
            <th width="200">Application</th>
            <th>Preview</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Inverse Kinematics Derivation - <a href="https://colab.research.google.com/github/PTC-Education/PTC-API-Playground/blob/main/Inverse_Kinematics.ipynb">click here to see notebook</a></td>
            <td style="text-align:center"><img src="/docs/solutions/onshapedx/Analyze.jpg" width="350" alt="Inverse Kinematics"/></td>
        </tr>
        <tr>
            <td>Google Sheets Dashboard - <a href="https://colab.research.google.com/github/PTC-Education/PTC-Education.github.io/blob/master/Google_Sheets_AL5D_Test.ipynb">click here to see notebook</a></td>
            <td style="text-align:center"><iframe width="350" height="220" src="https://www.youtube.com/embed/_fo_ENMdvEg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
        </tr>
        <tr>
            <td>Motion Simulation GIF Generator - <a href="https://colab.research.google.com/github/PTC-Education/PTC-Education.github.io/blob/master/Motion_Simulation_GIF_Generator.ipynb">click here to see notebook</a></td>
            <td style="text-align:center"><img src="/docs/solutions/onshapedx/OnshapeGif.gif" width="350" alt="Inverse Kinematics"/></td>
        </tr>
    </tbody>
</table>

<br>
</div>
<br>

<a name="Monitor"></a>
<div class="container"><h2>Monitor</h2>
Now you can start connecting Onshape to your edge devices and create a real-time digital twin in Onshape to monitor the physical device.
<br>
<br>
<table>
    <thead>
        <tr>
            <th width="200">Application</th>
            <th>Preview</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>UR3e Digital Twin - <a href="https://colab.research.google.com/github/PTC-Education/PTC-Education.github.io/blob/master/UR3e_Onshape_Monitor_Digital_Twin_with_ThingWorx.ipynb">click here to see notebook</a></td>
            <td style="text-align:center"><img src="/resources/UR3OnshapeDigitalTwin.gif" width="350" alt="UR3 Digital Twin"/></td>
        </tr>
        <tr>
            <td>Microbit Digital Twin - <a href="https://colab.research.google.com/github/PTC-Education/PTC-API-Playground/blob/main/MicroBit_Onshape_Digital_Twin.ipynb">click here to see notebook</a></td>
            <td style="text-align:center"><iframe width="350" height="220" src="https://www.youtube.com/embed/Z0HO4WPtZZ0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
        </tr>
    </tbody>
</table>
<br>
</div>
<br>

<a name="Control"></a>
<div class="container"><h2>Control</h2>
Once your edge device is connected to Onshape, you can use the model as your interface for controlling the movement and logic of your physical machine.
<br>
<br>
<table>
    <thead>
        <tr>
            <th width="200">Application</th>
            <th>Preview</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>AL5D PLTW Robot Arm Digital Twin - <a href="https://colab.research.google.com/github/PTC-Education/PTC-API-Playground/blob/main/AL5D_Digital_Twin_Demo.ipynb">click here to see notebook</a></td>
            <td style="text-align:center"><iframe width="350" height="220" src="https://www.youtube.com/embed/bZ5IoCWHz4M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
        </tr>
        <tr>
            <td>Microbit Control and Monitor - <a href="https://colab.research.google.com/github/PTC-Education/PTC-API-Playground/blob/main/MicroBit_Onshape_Digital_Twin.ipynb">click here to see notebook</a></td>
            <td style="text-align:center"><iframe width="350" height="220" src="https://www.youtube.com/embed/RyJVVVvLYSI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
        </tr>
    </tbody>
</table>
<br>
</div>

<!-- 

<br>
<br>
<br>

<h2>Organized by Edge Connectivity Below</h2>

<div class="container"><h3>Serial Connections</h3>
Below are examples using serial connections to edge devices plugged into your computer.
<h4><a href="https://colab.research.google.com/github/PTC-Education/PTC-API-Playground/blob/main/MicroBit_Onshape_Digital_Twin.ipynb">Microbit Onshape Digital Twin</a></h4>
<iframe width="560" height="315" src="https://www.youtube.com/embed/Z0HO4WPtZZ0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>
<br>
<h4><a href="https://colab.research.google.com/github/PTC-Education/PTC-API-Playground/blob/main/AL5D_Digital_Twin_Demo.ipynb">AL5D PLTW Robot Arm Onshape Digital Twin</a></h4>
<iframe width="560" height="315" src="https://www.youtube.com/embed/bZ5IoCWHz4M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<br>
<br>

<div class="container"><h3>Local Network Connections</h3>
Below are examples using serial connections to edge devices plugged into your computer.
<h4><a>Ender 3 Digital Twin</a></h4>
<iframe width="560" height="315" src="https://www.youtube.com/embed/rcr2VtXvAVk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->