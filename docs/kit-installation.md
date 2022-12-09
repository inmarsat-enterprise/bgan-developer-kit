## BGAN Developer Kit Installation

>:warning: WORK IN PROGRESS FOR PHYSICAL KIT/ACCESSORIES

>:information_source: The intent of the kit is to run your application using a
simulation of the BGAN network prior to the actual network, to determine
settings changes and characterize expected data use.

## Run in BGAN Simulation Mode

1. Connect an Ethernet cable between the Raspberry Pi's main Ethernet port
and your local Internet connection (e.g. router).

1. Connect a USB/Ethernet adapter to one of the Raspberry Pi's USB ports.

1. Connect your IoT device to the Ethernet/USB adapter.

1. Power up the Raspberry Pi. After it has booted you will be able to find
a WiFi network SSID: **`FieldEdge-<id>`** where `<id>` is a 4-character unique
identifier based on the Pi's Ethernet MAC address.

1. Attach to the Pi's WiFi access point with a tablet, PC or smartphone and
use a browser to go to http://fieldedge

    >If the fieldedge URL does not resolve, try using http://192.168.253.1

1. Select the **Data** tab using the FieldEdge GUI.

1. Click the **BGAN Simulation** toggle button to enable simulation over your
local Internet connection.

    >:warning: While the BGAN simulator is active, queries and responses to
    the Pi will be slower than normal, as all packets get delay added.

1. Power up your IoT device and set it to run as you would normally.

1. On the FieldEdge GUI **Data** page, select a duration and

## Install the BGAN Terminal Outdoors

Depending on the make/model of BGAN terminal you are using, the installation
instructions may vary. Fixed terminals must be pointed toward the satellite,
while mobile terminals need to be mounted flat with a clear view of the sky in
the direction of the satellite.

Gather the materials needed to complete your installation:

* BGAN terminal
* Long Ethernet and/or Power Cable with power supply
* Tripod mount assembly (if provided - Fixed terminal)
* Magnetic mount assembly (if provided - Mobile terminal)
* BGAN Pointer app
* FieldEdge "black box" (Raspberry Pi)
* Your IoT Edge device (unless running Inmarsat IoT Demo application)

1. Using the long Ethernet cable, connect the Raspberry Pi to the BGAN
terminal's main Ethernet port.

1. Connect your IoT device to the Ethernet/USB adapter connected to the Pi.

[Back to Developer Kit Quick Start](../README.md#Getting-Started)