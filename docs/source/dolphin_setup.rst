=============
Dolphin Setup
=============

Configuring Dolphin
-------------------
.. important::
    :ref:`Always use the latest beta build of Dolphin for NetPlay.`

Download the latest Dolphin Beta
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The `latest Dolphin Emulator Beta`_ includes bug fixes, performance enhancements, and other improvements to streamline your Netplay process. 
It is also supported by the Dolphin developers should you run into any issues, unlike *Slippi* or other *Faster Melee variants*.

.. warning::
    :ref:`Please refrain from using any versions or variations of Slippi or Faster Melee. The project maintainer for Slippi has explicitly stated their preference against using these for other games, and there are valid reasons for this request.`

.. _`latest Dolphin Emulator Beta`: https://dolphin-emu.org/download/

Recommended Settings for Dolphin
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

It is recommended you enable/disable the following settings:

Settings

::

    GENERAL:
    Enable Cheats = ON
    Auto Update = ON (BETA)

    INTERFACE:
    Show On-Screen Display Messages = ON

Graphics

::

    GENERAL:
    Show FPS = ON
    Show NetPlay Ping = ON

NetPlay

::

    DATA (Top Left Menu Bar):
    Sync Saves = OFF
    Sync AR/Gecko Codes = OFF

    NETWORK
    Fair Input Delay = ON

.. note::
    :ref:`Right click game > Host with NetPlay to access the NetPlay settings.`

After all these steps, you will set up your controller to inferface with the game under the Controllers option.

Configuring the Game
--------------------

Getting the Game
^^^^^^^^^^^^^^^^

The `Kirby Air Ride Hack Pack`_ is the version used for NetPlay. It includes various improvements that can be viewed `on this page`_

.. _`Kirby Air Ride Hack Pack`: https://mega.nz/file/IyIl2J4A#GagWAl2cn_jpSdBGqq3u7AkF7bPkR6BEzZw5v5C4Z6U

.. _`on this page`: https://kirbyairri.de/en/latest/hack_pack_features.html

Importing Gecko Codes
^^^^^^^^^^^^^^^^^^^^^

You will import Gecko Codes in order to provide over 200+ Gecko Codes and default-enabled NetPlay-based codes. Download the Gecko Codes by following instructions below:

**Kirby Air Ride Hack Pack**

`Right Click Me > Save Link As`_

**Kirby Air Ride**

`Right Click This > Save Link As`_

**Gecko Code Modifier Guide**

`You know the drill.`_

.. _`Right Click Me > Save Link As`: https://raw.githubusercontent.com/EternalllZM/rtd-kar/main/docs/source/media/gecko_codes/KHPE01.ini

.. _`Right Click This > Save Link As`: https://raw.githubusercontent.com/EternalllZM/rtd-kar/main/docs/source/media/gecko_codes/GKYE01.ini

.. _`You know the drill.`: https://raw.githubusercontent.com/EternalllZM/rtd-kar/main/docs/source/media/gecko_codes/modifier_guide.txt

Place these files into your **User/Gamesettings** or **Sys/Gamesettings** Dolphin directory folder, depending on whether you are using a portable install.

.. hint::
    :ref:`A portable install will use User/Gamesettings.`

Everything is now set. Continue on in this guide to host/connect to a netplay session.