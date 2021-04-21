---
layout: doc
title: Digital Twin Technologies
permalink: /docs/tech/twin
---

# Digital Twin (IoT or AR)

## ThingWorx
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Resource&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description | 
|---|---|
| [Hello ThingWorx!](https://apps.ptc.com/schools/curriculum/DX/HelloThingWorx.pdf) | A simple Hello World ThingWorx example that shows how to use REST API to make a simple IoT temperature dashboard.  ThingWorx and Vuforia Studio both require knowledge of JavaScript. [Learn JS at W3Schools.com](https://www.w3schools.com/js/) |
| [ThingWorx Developer Portal - Learning Pathways](https://developer.thingworx.com/en/resources/learning-paths) | A great place to start with ThingWorx, the Developer Portal contains tons of free resources for learning and building IoT solutions with ThingWorx. Specifically, this course is a good place to start: [Getting Started on the ThingWorx Platform](https://developer.thingworx.com/en/resources/learning-paths/getting-started-on-thingworx-platform)|
|[Monitor Plant Equipment Using Asset Advisor](https://developer.thingworx.com/en/resources/guides/mfg-apps-hosted-asset-advisor)|ThingWorx can optionally include some out-of-the-box Manufacutring Apps, to Monitor and Control a manufacturing systems; this learning path is a good starting point.|
|[How to Display Data in Charts](https://developer.thingworx.com/en/resources/guides/display-data-charts)|This guide will show you how to graphically display multiple data points in a various charts.|
|[ThingWorx help on PTC Support](https://support.ptc.com/help/thingworx/platform/r9/en/index.html#page/ThingWorx%2FHelp%2FComposer%2FSecurity%2FUsers%2FUsers.html%23)|The ThingWorx Platform 9 Help Center contains the latest information about the ThingWorx Platform. You will find detailed information about modeling, server-side scripting, and a variety of other topics. Whether you are a developer or system administrator, this Help Center contains topics pertinent to your ThingWorx journey.|
|[How to send alerts over text with Twilio](http://support.ptc.com/help/thingworx_hc/thingworx_8_hc/en/#page/ThingWorx%2FHelp%2FExtensibility%2FTwilio.html%23%26_ga%3D2.70454672.1483803700.1580137650-2099000272.1553708236)|The ThingWorx Twilio extension provides the ability to send SMS text and voice messages from ThingWorx through the Twilio communication platform.|
|[How to send alerts over email.](http://support.ptc.com/help/thingworx_hc/thingworx_8_hc/en/#page/ThingWorx%2FHelp%2FExtensibility%2FMail.html%23%26_ga%3D2.115040967.1309540450.1579614259-2099000272.1553708236)|The ThingWorx Mail extension provides the ability to read and send e-mails from ThingWorx through external SMTP mail servers that are made available to it.|
|[Purging Runtime Data](https://support.ptc.com/help/thingworx_hc/thingworx_8_hc/en/index.html#page/ThingWorx/Help/ModelandDataBestPractices/purgingdata.html)|While PTC does not have an official recommendation on how much data to store, since it is heavily dependent on the use case, it is recommended to have a plan in place for any production system to purge the old data for performance reasons.|
|[Installing ThingWorx on Windows - Guide](https://apps.ptc.com/schools/curriculum/DX/ThingWorx-Installation-Guide.pdf)|PTC Academic Guide for Installing ThingWorx on Windows. For local/on-prem ThingWorx installation administrators.|
|[Utilizing ThingWorx Projects](https://apps.ptc.com/schools/curriculum/DX/Utilizing-ThingWorx-Projects.pdf)|Learn to use projects to organize, export and import entities in ThingWorx. |
|[Connect Raspberry Pi to ThingWorx](https://developer.thingworx.com/resources/guides/thingworx-raspberry-pi-quickstart)|Connect a Raspberry Pi to ThingWorx using the Edge Micro Server (EMS).|
|[LabVIEW ThingWorx Integration](https://drive.google.com/drive/folders/1qsV-N3O4sMqzUFs6XQL8vnG4lQ4PpR4_)|Professor Chris Rogers from Tufts University created a library of LabVIEW VI's for reading and updating ThingWorx properties from directly in LabVIEW.|

## Other IoT Technolgies
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Resource&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description | 
|---|---|
| [Learn About IOT Using Airtable](https://github.com/PTC-Academic/DX-Resources/blob/master/Curriculum%20Resources/DX-Exercises/IOT-with-Airtable.md) | How to setup an Airtable database service to connect to Vuforia Spatial Toolbox. Airtablle can be used as a way to store Spatial Toolbox data online, accessible through an API key. |

## Kepware
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Resource&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description | 
|---|---|
|[Kepware Website](https://www.kepware.com/en-us/) | Factory-wide Connectivity for access to the right data, at the right time. [Download a free demo.](https://www.kepware.com/Demo-Downloads/Edge-Thank-You-Page?product=d41a2c0a-e93b-474a-bee3-14c1d27e9428) |
|[How to Connect Kepware to ThingWorx, Industrial Connections Example](http://support.ptc.com/help/thingworx_hc/thingworx_8_hc/en/#page/ThingWorx%2FHelp%2FComposer%2FIndustrialConnections%2FIndustrialConnectionsExample.html%23)|Using the Industrial Connections in ThingWorx, you can connect to ThingWorx Kepware Server to model, configure, and bind tags that exist in ThingWorx Kepware |||Server to Things in the ThingWorx model.|
|[BYU Smart Manufacturing Instructional Video](https://www.youtube.com/watch?v=8w3yWtPCTsk)|Video showcasing how easy it is to make your factory smart with Thingworx and Kepware|
|[Connect Industrial Devices and Systems](https://developer.thingworx.com/resources/guides/thingworx-kepware-server-guide)|This guide has step-by-step instructions for connecting ThingWorx Kepware Server to ThingWorx Foundation.|


## Other Edge Devices
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Resource&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description | 
|---|---|
| [OPC UA Client](https://www.kepware.com/en-us/products/kepserverex/drivers/opc-ua-client/) | For Raspberry Pi and Arduino, Kepware is not used to connect to ThingWorx. If you would like to have Kepware as the connectivity method you would likely need to use this OCP UA Client, but I am less familiar with this architecture: |
| [Connect Raspberry Pi to ThingWorx](https://developer.thingworx.com/resources/guides/thingworx-raspberry-pi-quickstart) | Raspberry Pi Resources |
 | [Connect an Arduino Developer Board Guide](https://developer.thingworx.com/resources/guides/connect-adafruit-feather) | Arduino Resources |
 | [KepServerEx and LabVIEW](https://www.kepware.com/getattachment/151e8138-b6f5-4e7a-8e01-e6dab30da3d0/LabVIEW_Connectivity_Guide.pdf) | NI Resources |

## Vuforia Studio
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Resource&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description | 
|---|---|
|[Vuforia Studio Academic Installation Guide](https://apps.ptc.com/schools/curriculum/DX/VS-Academic-Install.pdf)|Installing Vuforia Studio (local AR authoring enviroinment), for Academic Vuforia Studio Users|
|[Vuforia Studio Tutorials and FAQs](http://support.ptc.com/help/vuforia/studio/en/#page/Studio_Help_Center%2FTutorialWelcome.html%23)|Tutorials and FAQs for various Vuforia Studio experience levels.|
| [Search results on ThingWorx Developer Portal for "Vuforia"](https://developer.thingworx.com/en/resources/learning-paths#stq=vuforia&stp=1) | The results include several useful learning materials; some specfically included here...| 
|[Get Started with Vuforia Studio](https://developer.thingworx.com/resources/guides/getting-started-vuforia-studio)| This Getting Started guide is designed to introduce Developer Portal users to Vuforia Studio.|
|[Create an Augmented Reality (AR) Experience](https://developer.thingworx.com/resources/guides/studio-ar-experience-quickstart)| In this exercise, you'll combine 3D CAD models and 2D Widgets into an Experience that displays on mobile devices. |
|[Develop an AR Experience Demo](https://developer.thingworx.com/resources/guides/blue-pump-ar-tutorial)| You’ll build a pump demonstration, and we’ll show you how to capture, store, analyze, and visualize data utilizing Vuforia Studio. |
|[Extend Studio Functionality with Javascript:](https://developer.thingworx.com/resources/guides/extend-studio-javascript)| Explore the benefits of using JavaScript with Studio to extend the capabilities and enhance your AR Experiences |
| [Create a Model Hierarchy](http://apps.ptc.com/schools/curriculum/DX/Vuforia-Studio-Model-Hierarchy.pdf) | This document outlines the steps to create a model hierarchy in Vuforia Studio to more easily animate motion of an entire assembly |
|[Bind ThingWorx Data to a 3D Widget](http://support.ptc.com/help/vuforia/studio/en/#page/Studio_Help_Center%2FBeginnerBindTWXData.html%23)|A short tutorial that shows how to add ThingWorx data to an Experience and bind it to a widget.|
|[How to grant users publish permissions within Vuforia Studio](https://www.ptc.com/en/support/article/CS268110)|This article contains instructions on how to manage common user permissions tasks in Vuforia Studio.|
|[Configuring Vuforia Studio & ThingWorx For Academic Use Cases](https://apps.ptc.com/schools/curriculum/DX/VuforiaStudio-AcademicConfiguration.pdf)|This guide outlines the requirements and best practices for leveraging ThingWorx Composer for academic IoT and AR education using ThingWorx and Vuforia Studio.|
|[How to Create a Model Hierarchy in Vuforia Studio](https://apps.ptc.com/schools/curriculum/DX/Vuforia-Studio-Model-Hierarchy.pdf)|Used to create kinematic constrained asseblies in Vuforia Studio (for example, a 6-axis robot)|

## Vuforia Engine (SDK)
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Resource&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description | 
|---|---|
| [Vuforia (SDK) Developer Portal](https://developer.vuforia.com) | Resources for learning how to leverage Vuforia Engine (SDK). |
|[Vuforia Quick Installation Guide - Windows](https://apps.ptc.com/schools/curriculum/DX/Install_Vuforia.pdf)|How to install the Vuforia Engine/SDK in Unity.|
|[Vuforia Quick Installation Guide - MacOS](https://apps.ptc.com/schools/curriculum/DX/Install_Vuforia_MacOS.pdf)|How to install the Vuforia Engine/SDK in Unity.|
|[Add an Image Target to Your Experience ](https://apps.ptc.com/schools/curriculum/DX/Add%20an%20Image%20Target%20and%20CAD%20File.pdf)|This guide will show you how to Add an Image Target to Your Experience and Import Pre-Existing CAD Files |
|[From PTC Creo 3.0 to Vuforia 5.5](https://apps.ptc.com/schools/curriculum/DX/Creo_to_Vuforia.pdf)|In this guide you will learn how to Augment your PTC Creo 3.0 models with PTC Vuforia|

## Vuforia Spatial Toolbox
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Resource&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description | 
|---|---|
| [Vuforia Spatial Toolbox](https://spatialtoolbox.vuforia.com) | The Vuforia Spatial Toolbox and Vuforia Spatial Edge Server make up a shared research platform for exploring spatial computing. |
|[Video tutorials](https://www.youtube.com/playlist?list=PLhL0fv9JyKMaWhaHmm21J6mgpp841zYYw)|Vuforia Spatial Toolbox Tutorials from the Tufts Center for Engineering Education and Outreach (CEEO)|

## Vuforia Expert Capture
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Resource&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description | 
|---|---|
| [Transform Work Instruction with Vuforia Expert Capture](https://www.ptc.com/en/products/vuforia/vuforia-expert-capture) | Learn more about expert capture here, or reach out to PTC for a demo. |

## Vuforia Chalk
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Resource&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description | 
|---|---|
| [Remote Assistance Powered by Augmented Reality](https://www.ptc.com/en/products/vuforia/vuforia-chalk) | Learn more about expert capture here, or reach out to PTC for information.  |
|[Vuforia Chalk - Introduction Series](https://www.youtube.com/playlist?list=PLrCBNJga3kdFt0-Ss_O_D1hlh2-Sms02S)|An introduction video series to get started with Vuforia Chalk.|
|[Installing Vuforia Chalk Guide](https://apps.ptc.com/schools/curriculum/DX/Chalk_guide.pdf)|A written guide that walks a user through intalling Vuforia Chalk.|