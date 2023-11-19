=============
NetPlay Setup
=============

Now that your Dolphin is ready for playing the game, we can move forward with hosting/connecting to NetPlay sessions.

.. warning::
    :ref:`Make sure to utilize a wired (Ethernet) connection when engaging in NetPlay. Wireless (Wi-Fi) connections are prone to instability and can result in issues such as lag and instability during gameplay.`

.. note::
    :ref:`The guide doesn't include instructions for setting up NetPlay via server browser, as Dolphin already provides documentation on configuring this feature. 
    However, if you're familiar with the process, you're welcome to utilize this option.`

Hosting NetPlay
---------------

Host with Netplay
^^^^^^^^^^^^^^^^^

Right Click > Host with NetPlay

    .. image::  /media/netplay_setup/ns-host_with_netplay.png

Verify and Copy Information
^^^^^^^^^^^^^^^^^^^^^^^^^^^

Verify you are hosting Kirby Air Ride Hack Pack > Copy Room ID > Ensure Dolphin Revisions match.

    .. image::  /media/netplay_setup/ns-host_with_netplay2.png
    
Finalize Setup
^^^^^^^^^^^^^^

Share the code with your NetPlay partner to facilitate their connection. Afterward, adjust your buffer settings. 
There isn't a specific formula to follow for buffer settings. 
Instead, gradually increase the buffer until you achieve consistently smooth 60FPS gameplay. 
Adjusting the buffer in this way should help optimize the gameplay experience.

.. important::
    :ref:`Ensure you are setting up your Gecko Codes, located at the bottom of the page.`

Connecting NetPlay
------------------

Connect to Netplay
^^^^^^^^^^^^^^^^^^

Tools > Connect with Netplay *OR* Browse NetPlay sessions

    .. image::  /media/netplay_setup/ns-connect_with_netplay2.png

Traversal Connection
^^^^^^^^^^^^^^^^^^^^

Connection Type Traversal > Input Code received from Host

    .. image::  /media/netplay_setup/ns-connect_with_netplay2.png

Configuring Gecko Codes
-----------------------

Accessing Gecko Codes
^^^^^^^^^^^^^^^^^^^^^

Previously covered in the `Dolphin Setup`_, you will navigate to the Gecko Codes and ensure your Fullscreen codes are enabled.

Right Click Game > Properties > Gecko Codes Tab

    .. image::  /media/netplay_setup/ns-gecko_codes.png

.. _`Dolphin Setup`: https://kirbyairri.de/en/latest/dolphin_setup.html

Fullscreen Codes
^^^^^^^^^^^^^^^^

You will set fullscreen codes corresponding to your GCN controller port as shown above.

.. note::
    :ref:`Using fullscreen codes normally cause a desynchronization on a frame within the thousands, but it typically isn't game-breaking. You can generally ignore this desync unless players exhibit erratic movement or get stuck on walls.`