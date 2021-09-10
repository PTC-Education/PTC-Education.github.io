---
layout: doc
title: Robotics &amp; Mechatronics
permalink: /docs/solutions/robotics
description: This page shares ways that Onshape can be used for more than traditional mechanical design. Most of this work uses the Onshape API Snippets Library in Google Colab or Jupyter Notebooks.
---
<style>                                     
    #frame { 
        width: 100%; 
        height: 100%; 
        resize: height; 
    } 
</style>

<h2>Robotics & Mechatronics</h2>
<div class="container">
This page documents how PTC technologies can be used to teach robotics to students and enable researchers to push the boundaries of what's possible with connected machines. 
</div>
<br>

<div class="container">
<h3>Spatial Computing</h3>
<div class="columns is-vcentered is-centered is-multiline ">
    <div class="column is-one-half">
        <p><a href="https://spatialtoolbox.vuforia.com/">Vuforia Spatial Toolbox</a> is an open-sourced research platform for exploring spatial computing. In addition to <a href="https://spatialtoolbox.vuforia.com/docs/use">the tutorials on their website</a>, the PTC Education team has developed additional add-ons and activities to help you deploy the spatial edge server in new ways or connect with educational hardware.</p>
    </div>
    <div class="column is-one-half is-vcentered is-centered">
        <p style="text-align:center"><img src="/docs/solutions/RPiToolboxArduinoALD5.gif" width="60%" alt="Onshape Public Search"/></p>
    </div>
</div>
<table>
    <thead>
        <tr>
            <th width="200">Topic</th>
            <th>Preview</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>This guide shows you how to install the Spatial Edge Server on a Raspberry Pi and turn it into a WiFi hotspot so you can connect and control any device on the local network, no internet connection required. <a href="https://github.com/PTC-Education/RaspberryPi-SpatialToolbox-WifiHotspot">Click here to learn more.</a></td>
            <td style="text-align:center"><img src="/docs/solutions/RPiToolboxArduinoALD5.gif" width="50%" alt=""/></td>
        </tr>
        <tr>
            <td>Our team has created an additional add-on library with tools and hardware interfaces for expanded capability and connectivity. <a href="https://github.com/PTC-Education/vuforia-spatial-extension-addon">Click here to learn more.</a></td>
            <td style="text-align:center"><iframe width="60%" height="220"  src="https://www.youtube.com/embed/FGho56WVhwA" title="YouTube video player" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
        </tr>
        <tr>
            <td>This guide shows you how to get started with connecting a Spike Prime to the Vuforia Spatial Toolbox and monitoring and controlling it with spatial computing. <a href="https://github.com/PTC-Education/LEGO-Spatial-Computing-Project">Click here to learn more.</a></td>
            <td style="text-align:center"><img src="/docs/solutions/LEGOtoolbox.gif" width="50%" alt=""/></td>
        </tr>
        <tr>
            <td>This is a hello world guide for getting started with connecting an Arduino Uno to the Spatial Toolbox with the basic interfaces add-ons library. <a href="https://github.com/PTC-Education/DX-Resources/tree/master/Curriculum_Resources/DX-Exercises/Vuforia%20Spatial%20Toolbox%20-%20Arduino%20Hello%20World">Click here to learn more.</a></td>
            <td style="text-align:center"><img src="/resources/ArduinoLightSwitch.gif" width="50%" alt=""/></td>
        </tr>
    </tbody>
</table>
</div>
<br>

<div class="container">
    <h3>Onshape</h3>
       <div class="columns is-vcentered is-centered is-multiline ">
            <div class="column is-one-half">
                <p>One of the many benefits of Onshape is the vast amounts of communithy create models and libraries that are publicly available in the cloud. Before modeling a part yourself, it might be worth searching in "Public" to see if someone else has already made it publicly available</p>
            </div>
            <div class="column is-one-half is-vcentered is-centered">
                <p style="text-align:center"><img src="/docs/solutions/OnshapePublicSearch.gif" width="100%" alt="Onshape Public Search"/></p>
            </div>
        </div>
    <h4>Libraries of Robotics Parts</h4>
    <p>The community of Onshape Education users has developed a number of part libraries for different robotics building systems, enabling students to design their robots as an Onshape Assembly.</p>
    <table>
        <thead>
            <tr>
                <th width="200">Topic</th>
                <th>Preview</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><a href="https://cad.onshape.com/documents/f80b668b3ae9c732b3c7d91b/w/cc29213b0eb52b9d3bc554e2/e/405c61eae74e61cae1728931">Click here to see the public library of parts for LEGO Education's Spike Prime Kit.</a></td>
                <td style="text-align:center"><a href="https://cad.onshape.com/documents/f80b668b3ae9c732b3c7d91b/w/cc29213b0eb52b9d3bc554e2/e/405c61eae74e61cae1728931"><p style="text-align:center">
                <img src="/docs/solutions/SpikePrimeKit.png" width="50%" alt=""/></p></a></td>
            </tr>
            <tr>
                <td><a href="https://cad.onshape.com/documents/5782e53fe4b0b7679dbf9f2c/w/b62de756a6f06dfc82b8fcef/e/bdbaf7b4a0cbf3da59b1e980">Click here to see the public library of parts for the VEX Robotics Kit.</a></td>
                <td style="text-align:center"><a href="https://cad.onshape.com/documents/5782e53fe4b0b7679dbf9f2c/w/b62de756a6f06dfc82b8fcef/e/bdbaf7b4a0cbf3da59b1e980"><p style="text-align:center">
                <img src="/docs/solutions/VexKit.png" width="50%" alt=""/></p></a></td>
            </tr>
            <tr>
                <td><p><a href="/docs/solutions/onshapedx">Click here</a> to check out some of the ways we are using Onshape models as digital twins by connecting them to physical robots through Python Noteboooks.</p></td>
                <td style="text-align:center"><a href="/docs/solutions/onshapedx"><p style="text-align:center"><img src="/resources/UR3OnshapeDigitalTwin.gif" width="65%" alt="Onshape Public Search"/></p></a></td>
            </tr>
        </tbody>
    </table>
</div>
<br>

<div class="container">
    <h3>ThingWorx</h3>
    <p>ThingWorx is PTC's Internet of Things platform which can be used to develop any number of applications for connected robots. Check out some of the resources below for getting started materials or lab activities involving robots and ThingWorx.
    <h4>REST API Snippets</h4>
    <p><a href="https://colab.research.google.com/github/PTC-Education/PTC-API-Playground/blob/main/ThingWorx_API_Snippets.ipynb">Click here to find the ThingWorx API Snippets in Google Colab.</a></p>
    <table>
        <thead>
            <tr>
                <th width="200">Topic</th>
                <th>Preview</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><a href="https://www.youtube.com/embed/dxyGW-UyQnM">ThingWorx REST API Setup</a></td>
                <td style="text-align:center"><iframe width="70%" height="220" src="https://www.youtube.com/embed/dxyGW-UyQnM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
            </tr>
            <tr>
                <td><a href="https://www.youtube.com/embed/OzvIGDFnqCs">ThingWorx Services with REST API</a></td>
                <td style="text-align:center"><iframe width="70%" height="220" src="https://www.youtube.com/embed/OzvIGDFnqCs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
            </tr>
        </tbody>
    </table>
    <h4>ThingWorx Analytics</h4>
    <table>
        <thead>
            <tr>
                <th width="200">Topic</th>
                <th>Preview</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><a href="https://github.com/PTC-Education/UR3-Analytics">UR3 Analytics</a><br />This example demonstrates the usage of Thingworx Analytics to determine the weight of an object that a UR3 robot is holding.</td>
                <td style="text-align:center"><img src="UR3-Analytics-flow.png" width="100%" alt=""/></td>
            </tr>
        </tbody>
    </table>