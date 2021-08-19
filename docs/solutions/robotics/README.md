---
layout: doc
title: Robotics
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

<h2>Robotics</h2>
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
        <div class="columns is-vcentered is-centered is-multiline ">
            <div class="column is-one-fourth is-vcentered is-centered">
                <a href="https://github.com/PTC-Education/RaspberryPi-SpatialToolbox-WifiHotspot"><p style="text-align:center">
                <img src="/docs/solutions/RPiToolboxArduinoALD5.gif" width="70%" alt=""/></p>
                <div class="subtitle" style="text-align:center">Raspberry Pi Wifi Hotspost</div>
                </a>
            </div>
            <div class="column is-one-fourth">
                <a href="https://github.com/PTC-Education/vuforia-spatial-extension-addon">
                <iframe id="frame" src="https://www.youtube.com/embed/FGho56WVhwA" title="YouTube video player" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                <div class="subtitle" style="text-align:center">Extension Addons</div>
                </a>
            </div>
            <div class="column is-one-fourth">
                <a href="https://github.com/PTC-Education/LEGO-Spatial-Computing-Project"><p><img src="/docs/solutions/LEGOtoolbox.gif" alt=""/></p>
                <div class="subtitle" style="text-align:center">LEGO Spike Prime Spatial Computing</div>
                </a>
            </div>
            <div class="column is-one-fourth">
                <a href="https://github.com/PTC-Education/DX-Resources/tree/master/Curriculum_Resources/DX-Exercises/Vuforia%20Spatial%20Toolbox%20-%20Arduino%20Hello%20World">
                <p><img src="/resources/ArduinoLightSwitch.gif" alt=""/></p>
                <div class="subtitle" style="text-align:center">Arduino and Spatial Toolbox</div>
                </a>
            </div>
        </div>
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
        <div class="columns is-vcentered is-centered is-multiline ">
            <div class="column is-one-half">
                <a href="https://cad.onshape.com/documents/f80b668b3ae9c732b3c7d91b/w/cc29213b0eb52b9d3bc554e2/e/405c61eae74e61cae1728931"><p style="text-align:center">
                <img src="/docs/solutions/SpikePrimeKit.png" width="70%" alt=""/></p>
                <div class="subtitle" style="text-align:center">LEGO Spike Prime</div>
                </a>
            </div>
            <div class="column is-one-half is-vcentered is-centered">
                <a href="https://cad.onshape.com/documents/5782e53fe4b0b7679dbf9f2c/w/b62de756a6f06dfc82b8fcef/e/bdbaf7b4a0cbf3da59b1e980"><p style="text-align:center">
                <img src="/docs/solutions/VexKit.png" width="70%" alt=""/></p>
                <div class="subtitle" style="text-align:center">VEX Robotics</div>
                </a>
            </div>
        </div>
    <h4><a href="/docs/solutions/onshapedx">Onshape DX</a></h4>
        <div class="columns is-vcentered is-centered is-multiline ">
            <div class="column is-one-half">
                <p><a href="/docs/solutions/onshapedx">Click here</a> to check out some of the ways we are using Onshape models as digital twins by connecting them to physical robots through Python Noteboooks.</p>
            </div>
            <div class="column is-one-half is-vcentered is-centered">
                <p style="text-align:center"><img src="/resources/UR3OnshapeDigitalTwin.gif" width="65%" alt="Onshape Public Search"/></p>
            </div>
        </div>
</div>
<br>

<div class="container">
    <h3>ThingWorx</h3>
    <p>ThingWorx is PTC's Internet of Things platform which can be used to develop any number of applications for connected robots. Check out some of the resources below for getting started materials or lab activities involving robots and ThingWorx.
    <h4>REST API Snippets</h4>
    <p><a href="https://colab.research.google.com/github/PTC-Education/PTC-API-Playground/blob/main/ThingWorx_API_Snippets.ipynb">Click here to find the ThingWorx API Snippets in Google Colab.</a></p>
    <div class="columns is-vcentered is-centered is-multiline ">
        <div class="column is-one-half is-centered">
            <p class="is-centered"><iframe width="90%" height="220" src="https://www.youtube.com/embed/dxyGW-UyQnM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>
            <div class="subtitle" style="text-align:center">ThingWorx REST API Setup</div>
        </div>
        <div class="column is-one-half is-vcentered is-centered">
            <p><iframe width="90%" height="220" src="https://www.youtube.com/embed/OzvIGDFnqCs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>
            <div class="subtitle" style="text-align:center">ThingWorx Services with REST API</div>
        </div>
    </div>
    <h4>ThingWorx Analytics</h4>
    <div class="columns is-vcentered is-centered is-multiline ">
            <div class="column is-one-half">
                <a href="https://github.com/PTC-Education/UR3-Analytics"><p style="text-align:center">
                <img src="UR3-Analytics-flow.png" width="100%" alt=""/></p>
                <div class="subtitle" style="text-align:center">UR3 Analytics</div>
                </a>
            </div>
            <!-- <div class="column is-one-half is-vcentered is-centered">
                <a href="https://cad.onshape.com/documents/5782e53fe4b0b7679dbf9f2c/w/b62de756a6f06dfc82b8fcef/e/bdbaf7b4a0cbf3da59b1e980"><p style="text-align:center">
                <img src="/docs/solutions/VexKit.png" width="70%" alt=""/></p>
                <div class="subtitle" style="text-align:center">VEX Robotics</div>
                </a>
            </div> -->
    </div>