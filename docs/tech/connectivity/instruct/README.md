---
layout: doc
title: Vuforia Instruct Hello World
permalink: /docs/tech/connectivity/instruct
description: Instructions on getting started with Vuforai Instruct and Expert Capture
---

<div class="container"><h2>Vuforia Instruct and Expert Capture</h2>
<a href="https://www.ptc.com/en/products/vuforia/vuforia-instruct">Vuforia Instruct</a> is a product that allows you to very easily create CAD based work instructions. It works well with Vuforia Expert Capture, as you can guide workers around a 3D model target and deliver first-hand perspective of a procedure in the place around the model where it was carried out.
</div>

<div class="container"><h3>Getting Started</h3>
<ol>
    <li><h4>Logging In</h4>
    Start by going to <a href="https://go.studio.vuforia.com/portal/">the Vuforia portal</a>. You should see links to a number of different resources related to authoring, using, and analyzing augmented reality experiences. To start creating an experience, click "sign in" next to Vuforia Editor, which should <a href="https://go.studio.vuforia.com/editor">take you here</a>. If you have been added to an instance of Vuforia Instruct, you should be able to sign in with that email and password.
    </li>
    <li><h4>Creating a First Experience</h4>
    <img src="./instruct create new procedure.png" width="300"><br>
    From the top left you can click "Create" and "New Procedure". Give the procedure a name and click "Create" (don't worry about uploading a capture yet). 
    </li>
    <li><h4>Uploading a CAD Model</h4>
    <img src="./upload cad model.png" width="300"><br>
    Upload a CAD model by clicking the plus in the top left, select import assets, and 3D. <a href="https://support.ptc.com/help/vuforia/editor/en/#page/vuforia_editor%2Fassets_models.html">Click here</a> to see what file formats are supported. 
    </li>
    <li><h4>Adding CAD to Procedure</h4>
    <img src="./add 3d to procedure.png" width="300"><br>
    To create CAD-based work instructions, you can click "Add 3D to Procedure" at the top and add the CAD model that you've just uploaded. Once you import the model, you should see the 3D editor in the middle with the procedure steps on the right.
    </li>
    <li><h4>Add Steps to Procedure</h4>
    <img src="./adding steps.gif" width="300"><br>
    You can add steps to the procedure by clicking the plus on the right. Add a description and any image or video assets (like from Expert Capture) to a step, then you can add a point marker to the CAD model in the 3D editor.
    </li>
    <li><h4>Publish Procedure</h4>
    Once you are ready, you can publish the experience by clicking "Publish" tab in the top right corner, then clicking the "Publish" button. (NOTE: your user needs to have at least "Manager" permissions to publish an experience)
    </li>
    <li><h4>Manage View Access</h4>
    <img src="./manage published experiences.png" width="300"><br>
    Once the experience is published, there is one last step before you can use the experience in the Vuforia Vantage app. From the top right menu, click on your username, then click "Manage published procedures". Click on the procedure you've just published, and from the new menu make sure the proper users have view access.
    </li>
    <li><h4>Viewing Experience</h4>
    Once you've set the view permission, you can download a QR code of the experience from the same panel. On your device (phone, tablet, AR glasses, etc.), open the Vuforia Vantage app and scan the QR code. You should now be able to see your first published procedure
    </li>
</ol>
</div>