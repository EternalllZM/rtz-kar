=============
NetPlay Setup
=============

Now that your Dolphin is ready for playing the game, we can move forward with hosting/connecting to NetPlay sessions.

.. warning::
    :ref:`Ensure you use a wired (Ethernet) connection for NetPlay. Wireless (Wi-Fi) connections are unstable and may cause issues of lag and instability.`

.. note::
    :ref:`NetPlay browser setup is not covered in this guide, as there is already documentation via Dolphin on how to configure this. 
    However, you may use this option if you know how to.`

Hosting NetPlay
---------------

- **Host with Netplay**

Right Click > Host with NetPlay

    .. image::  /media/netplay_setup/ns-host_with_netplay.png

- **Verify and Copy Information**

Verify you are hosting Kirby Air Ride Hack Pack > Copy Room ID > Ensure Dolphin Revisions match.

    .. image::  /media/netplay_setup/ns-host_with_netplay2.png
    
- **Finalize Setup**

Provide the code to your NetPlay partner so that they are able to connect. After this, you will set your buffer. 
There is no formula for buffer that you should follow. Simply raise it until a smooth 60FPS gameplay is achieved.

.. important::
    :ref:`Ensure you are setting up your Gecko Codes, located at the bottom of the page.`

Connecting NetPlay
------------------

- **Connect to Netplay**

Tools > Connect with Netplay *OR* Browse NetPlay sessions

    .. image::  /media/netplay_setup/ns-connect_with_netplay2.png

- **Traversal Connection**

Connection Type Traversal > Input Code received from Host

    .. image::  /media/netplay_setup/ns-connect_with_netplay2.png

Configuring Gecko Codes
-----------------------

- **Accessing Gecko Codes**

Previously covered in the `Dolphin Setup`_, you will navigate to the Gecko Codes and ensure your Fullscreen codes are enabled.

Right Click Game > Properties > Gecko Codes Tab

    .. image::  /media/netplay_setup/ns-gecko_codes.png

.. _`Dolphin Setup`: https://kirbyairri.de/en/latest/dolphin_setup.html

- **Fullscreen Codes**

You will set fullscreen codes corresponding to your GCN controller port as shown above.

.. note::
    :ref:`Fullscreen codes will cause a desync that is not game-breaking. This desync can be ignored unless players are erratically moving or stuck on walls.`