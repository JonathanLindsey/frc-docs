.. include:: <isonum.txt>

Programming Radios for FMS Offseason
====================================

When using the :term:`FMS` Offseason software, the typical networking setup is to use a single access point with a single SSID and WPA key. This means that the radios should all be programmed to connect to this network, but with different IPs for each team. The Team version of the FRC\ |reg| Bridge Configuration Utility has an FMS Offseason mode that can be used to do this configuration.

Enter FMS Offseason Mode
------------------------

.. image:: images/programming-radios-for-fms-offseason/tools-fmsoffseason.png
   :alt: Click on "Tools" then "FMS-Lite Mode".

Click ``Tools`` -> ``FMS-Lite Mode`` to enter FMS-Lite Mode.

Enter SSID
----------

.. image:: images/programming-radios-for-fms-offseason/ssid.png
   :alt: Enter the network SSID in the dialog box.

Enter the SSID (name) of your wireless network in the box and click OK.

Enter WPA Key
-------------

.. image:: images/programming-radios-for-fms-offseason/wpa.png
   :alt: Enter the WPA Key (password) for this SSID.

Enter the WPA key for your network in the box and click OK. Leave the box blank if you are using an unsecured network.

Program Radios
--------------

.. image:: images/programming-radios-for-fms-offseason/program-radio.png
   :alt: Program the radio through the utility like normal for all of the radios at your event.

The Kiosk is now ready to program any number of radios to connect to the network entered. To program each radio, connect the radio to the Kiosk, set the Team Number in the box, and click Configure.

The kiosk will program OpenMesh, D-Link Rev A or D-Link Rev B radios to work on an offseason FMS network by selecting the appropriate option from the "Radio" dropdown.

.. note:: Bandwidth limitations and QoS will not be configured on the D-Link radios in this mode.

Changing SSID or Key
--------------------

If you enter something incorrectly or need to change the SSID or WPA Key, go to the Tools menu and click FMS-Lite Mode to take the kiosk out of FMS-Lite Mode. When you click again to put the Kiosk back in FMS-Lite Mode, you will be re-prompted for the SSID and Key.
